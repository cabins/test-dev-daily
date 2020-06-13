# HttpRunner学习笔记

[toc]

## HttpRunner安装

```bash
pip install -i https://pypi.douban.com/simple httprunner
```

检查一下HttpRunner的版本

```bash
hrun -V
```

如果出现了`ModuleNotFoundError: No module named 'allure'`的错误，用以下命令解决：

```bash
pip install allure-pytest
```

如果出现了`uploader extension dependencies uninstalled, install first and try again. install with pip: $ pip install requests_toolbelt filetype`的错误，用以下命令解决：

```
pip install requests_toolbelt filetype
```



## HttpRunner创建项目

```bash
hrun --startproject HelloWorld
```

