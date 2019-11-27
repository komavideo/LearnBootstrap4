padding和margin的使用
====================

## 知识点

* [p|m][location]-[size]

参考网页：

https://getbootstrap.com/docs/4.0/utilities/spacing/

### 用法说明

p:padding
m:margin

location:
- t, b, l, r
  - t:top
  - b:bottom
  - l:left
  - r:right
- x, y
  - x:lr
  - y:tb

size:
- 0
- 1:0.25rem
- 2:0.5rem
- 3:1.0rem
- 4:1.5rem
- 5:3.0rem
- auto

#### rem是个啥？

以根要素为基准，按照比例设定子元素的大小。

参照网页：

https://developer.mozilla.org/zh-CN/docs/Web/CSS/length

## 实战演习

~~~html
<style>
    .my-container {
        width: 200px;
        height: 200px;
        background: #ddd;
        margin-bottom: 5px;
    }
</style>
...
<div class="my-container pt-3 pl-3">
    <div class="bg-primary w-50 h-50 pt-1 pl-2">小马视频</div>
</div>
<div class="my-container px-3 py-3">
    <div class="bg-success w-100 h-100">小马视频</div>
</div>
~~~

## 课程文件

https://gitee.com/komavideo/LearnBootstrap4

## 小马视频频道

http://komavideo.com
