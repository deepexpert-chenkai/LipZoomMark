<h3>简介</h3>
一款支持图片缩放、拖动、旋转、添加标记的基于Jquery的插件。<br>
右键添加标记，左键按住移动鼠标可拖动，滚轮可以缩放画布。

<h3>使用方法</h3>
##初始化(Jquery自己引用好)

```
<div id="container" ><img src="./assets/demo.jpg"></div>
<script type="text/javascript">
	$('#container').ZoomMark();
</script>
```


##重置画布
```
$('#container').ZoomMark('reset');
```

##移动画布
```
$('#container').ZoomMark('move',20,20);//后面两个参数代表x,y轴的移动数值
```

##缩放画布
```
$('#container').ZoomMark('zoom',5);//后面的数字代表放大倍数，<1就是缩小
```

##旋转画布
```
$('#container').ZoomMark('rotate',90);
```

##修改标记颜色
```
$('#container').ZoomMark('changeSettings',{'markColor':'#d31145'});
```

##删除标记
```
$('#container').ZoomMark('deleteMark',id);
```

<h3>在线Demo</h3>

http://www.jq22.com/demo/LipZoomMark201805081119/
