理解响应式布局
============

## 知识点

* 屏幕大小的划分

参考网页：

https://getbootstrap.com/docs/4.0/layout/grid/#grid-options

### 屏幕大小的划分

Bootstrap4根据客户端显示屏幕的大小，分为以下几个分类：

* 超小（Extra small）
  - <576px
  - .col-*
* 小（Small）
  - ≥576px
  - .col-sm-*
* 中（Medium）
  - ≥768px
  - .col-md-*
* 大（Large）
  - ≥992px
  - .col-lg-*
* 超大（Extra large）
  - ≥1200px
  - .col-xl-*

## 实战演习

~~~html
<!-- 课题：基本的布局方式，但还不具有响应式功能，请先看一下目前的效果吧 -->
<div class="container">
    <div class="row">
        <div class="col bg-danger">
            1 of 2
        </div>
        <div class="col bg-success">
            2 of 2
        </div>
    </div>
    <div class="row">
        <div class="col bg-info">
            1 of 3
        </div>
        <div class="col bg-primary">
            2 of 3
        </div>
        <div class="col bg-warning">
            3 of 3
        </div>
    </div>
</div>
~~~

## 课程文件

https://github.com/komavideo/LearnBootstrap4

## 小马视频频道

http://komavideo.com
