# PROJECT 1
> 19302010009 钱麒丹

-----
## Project的完成情况
我以较高的完成度圆满完成了本次PJ的任务。
包括index，register，home，browser，search，my_photo，my_favor，upload，details这九个页面。
index.html为引导用户进入主页的登录页面。
> register.html为注册页面。

> home.html为网站主页。

> browser.html为筛选图片的浏览页。

> search.html为搜索图片的搜索页。

> my_photo.html为用户照片的页面。

> my_favor.html为用户收藏照片的页面。

> upload为用户上传照片的页面。

> details为照片的详情页面。

-----
## Bonus的完成情况
### Bonus1：更复杂的图片处理
自由版式图片的处理我使用了如下的解决方法。
```
.img-container {
    width: ...px;
    height: ....px;
}

.img-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

<div class="img-container">
    <img src="...">
</div>
```
将img元素放置在div块中，就可以通过修改div容器的长宽来修改显示出图片的长宽。同时将img元素的object-fit属性设置为cover后，img本身就不会被拉伸，并且img将居中在容器中显示，借此完成了非正方形图片的裁剪。
### Bonus2：响应式布局
主要解决方法是使用**流动式布局**为各个页面布局。比如使用百分比设定块和元素的宽度，以及设定块和元素最小的宽度来防止排版混乱。
### Bonus3：界面美观
主要解决方法是运用我的**审美能力**为块和元素添加样式。