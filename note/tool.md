# 编辑器sublime text3
## 快速运行python文件快捷设置
我的电脑-系统属性-高级-环境变量-Path,把python.exe的路径增加到Path看。
在sublime text3中Tools--Build System--New Build System,输入代码
```
{ "cmd": ["python", "$file"], "file_regex": "python$", "selector": "source.python" } 
```
保存为python3.sublime-build
接下来在sublime text中可运行ctrl+B快捷运行python文件