/*
Title: imageTool
Description: imageTool
*/

<p style="color: #ccc;margin-bottom: 30px;">来自于：开发者</p>

<ul id="tab" class="clearfix">
	<li class="active"><a href="#method-content">Method</a></li>
</ul>
<div id="method-content">

<div class="outline">
[openImage](#a1)
</div>

#**概述**

imageTool封装了android的系统相册，使用此模块可轻松实现对相册中图片名称，大小，路径读取功能


#**openImage**<div id="a1"></div>

打开系统相册并返回图片信息


openImage(callback(ret, err))



##callback(ret, err)

ret：

- 类型：JSON 对象

内部字段：

```js
{
	imgName:		//图片名称
	imgSize:                //图片大小
	imgPath:                //图片路径
}
```


##示例代码

```js
var imageTool = api.require('imageTool');


imageTool.openImage(function(ret, err){api.prompt({title:"信息",msg:"图片名称："+ret.imgName+"图片大小："+ret.imgSize+"图片路径："+ret.imgPath,buttons:["取消","确定"]});});
```

##补充说明

无

##可用性

Android系统

可提供的1.0.0及更高版本


