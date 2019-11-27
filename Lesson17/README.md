完善Tab菜单
==========

## 知识点

* nav
* nav-tabs
* nav-item
* nav-link
* tab-content
* tab-pane
* data-toggle="tab"

参考网页：

https://getbootstrap.com/docs/4.0/components/navs/

## 实战演习

~~~html
<section class="py-5">
    <h2 class="text-center">我爱NBA</h2>
    <div class="container">
        <ul class="nav nav-tabs">
            <li class="nav-item">
                <a href="#east" class="nav-link active" data-toggle="tab">东部(East)</a>
            </li>
            <li class="nav-item">
                <a href="#west" class="nav-link" data-toggle="tab">西部(West)</a>
            </li>
        </ul>
        <div class="tab-content py-3">
            <div id="east" class="tab-pane active">
                <p>2018年东部冠军是凯尔特人还是骑士？不会是猛龙吧？</p>
            </div>
            <div id="west" class="tab-pane">
                <p>西部冠军肯定是勇士了，不过火箭今天也很不错。</p>
            </div>
        </div>
    </div>
</section>
~~~

## 课程文件

https://gitee.com/komavideo/LearnBootstrap4

## 小马视频频道

http://komavideo.com
