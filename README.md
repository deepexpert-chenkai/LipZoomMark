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

在线Demo
