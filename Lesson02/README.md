Bootstrap4初次使用
==================

## 知识点

* Bootstrap4支持技术
* 从模板开始(Starter template)

### Bootstrap4支持技术

1. jQuery  
  https://jquery.com/
2. popper.js  
  https://popper.js.org/

### 从模板开始(Starter template)

进入Bootstrap官网，从文档页中提取出页面的初始模板。

http://getbootstrap.com/docs/4.0/getting-started/introduction/

## 实战演习1(CDN)

~~~html
<!doctype html>
<html lang="zh-cmn-Hans">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
~~~

## 实战演习2(本地引用)

下载Bootstrap4发行包，然后如下初始化模板页面。

http://getbootstrap.com/docs/4.0/getting-started/download/

~~~html
<html lang="zh-cmn-Hans">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="/bootstrap-4.0.0-dist/css/bootstrap.min.css">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="/bootstrap-4.0.0-dist/others/jquery-3.2.1.slim.min.js"></script>
    <script src="/bootstrap-4.0.0-dist/others/popper-1.12.9.min.js"></script>
    <script src="/bootstrap-4.0.0-dist/js/bootstrap.min.js"></script>
  </body>
</html>
~~~

## 课程文件

https://github.com/komavideo/LearnBootstrap4

## 小马视频频道

http://komavideo.com
