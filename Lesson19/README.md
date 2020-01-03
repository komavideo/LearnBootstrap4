制作提示框（Tooltip）
====================

## 知识点

* data-toggle="tooltip"
* data-placement

参考网页：

https://getbootstrap.com/docs/4.0/components/tooltips/

## 实战演习

~~~html
<div class="tab-content py-3">
    <div id="east" class="tab-pane active">
        <p>2018年东部冠军是
            <span class="font-weight-bold text-success" title="绿凯东部第一" data-toggle="tooltip" data-placement="top">凯尔特人</span>还是
            <span class="font-weight-bold text-danger" title="老詹没输" data-toggle="tooltip" data-placement="bottom">骑士</span>？不会是猛龙吧？</p>
    </div>
    <div id="west" class="tab-pane">
        <p>西部冠军肯定是勇士了，不过火箭今天也很不错。</p>
    </div>
</div>
...
<script>
    $(function(){
        'use strict';
        $('[data-toggle="tooltip"]').tooltip();
    });
</script>
~~~

## 课程文件

https://github.com/komavideo/LearnBootstrap4

## 小马视频频道

http://komavideo.com
