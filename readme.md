# 这是一个 Markdown 案例 readme.md

## 这里展示一下起步的 HTML

创建一个文件 `index.html`，并用编辑器将下边的文字填入这个文件。

```html
<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>HELLO</title>
    <link href="//cdn.bootcss.com/skeleton/2.0.4/skeleton.min.css" rel="stylesheet">
    <script src="//cdn.bootcss.com/jquery/1.11.3/jquery.min.js"></script>
  </head>
  <body>
    <h1>你好，世界！</h1>
  </body>
</html>
```

## 如何启动一个临时的 HTTP 服务器

首先你得保证你的PC已经安装了 **python** 环境，点击[这里](https://www.python.org/)下载。

安装 **python** 以后，你可以查看是否安装成功。

```shell
$ python --version
Python 2.7.10

```

这就表示 **python 2.7** 已经安装成功。

接下来启动 HTTP 服务器：

```shell
$ python -m SimpleHTTPServer 8000
Serving HTTP on 0.0.0.0 port 8000 ...

```

意思是你已经在当前文件夹下，启动了一个外网都可以访问的 HTTP 服务器，并且落在了 8000 端口上。

接下来你就可以访问这个资源了。


