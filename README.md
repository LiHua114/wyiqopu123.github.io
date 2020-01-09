<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta content="en-us" http-equiv="Content-Language" />
<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>主页</title>
</head>
<style>
/*下方这句不动它，翻译开始*/

* {
	padding: 0;
	margin: 0;
}

/*翻译
主页整体样式 
文本对齐︰ 中心;
背景色︰ #ffffff  使用夜间默认时修改为#000000即可
}
*/

body {
	text-align: center;
	background-color: #ffffff;
}

/*翻译
logo图标样式 
宽度︰ 128px;
高度︰ 80px;
最大宽度︰ 250px;
动画︰ flipInX 4s;
-webkit 动画︰ flipInX 4s
}*/


img.smaller {
	width: 96px;
	height: 96px;
	max-width: 96px;
	animation: flipInX 4s;
	-webkit-animation: flipInX 4s
}



/*翻译
logo添加文字样式 
字体大小︰ 2em;
白色空间︰ 正常;
自动换行︰ 断词;
文本修饰︰ 无;
颜色: #232323
}*/

.logo {
	font-size: 2em;
	white-space: normal;
	word-wrap: break-word;
	text-decoration: none;
	color: #232323
}

/*翻译
搜索栏字体样式 
宽度︰ 90%;
高度︰ 40px;
背景颜色︰ 透明;
边境︰ 无;
大纲︰ 0;
字体大小︰ 18px;
字体颜色: #426ab3;
填充︰ 0 20px;
边界半径︰ 50px
}*/

#search_input {
	width: 90%;
	height: 45px;
	background-color: transparent;
	border: none;
	outline: 0;
	font-size: 18px;
	color: #426ab3;
	padding: 0 20px;
	border-radius: 40px;
}

/*翻译
搜索框边距 
下边距︰ 30px;
上边距︰ 20px;
*/

.search_part {
	margin-bottom: 30px;
	margin-top: 20px;
}

/*翻译
跨度样式
显示︰ 阻止;
溢出︰ 隐藏;
左填充︰ 5px;
垂直对齐︰ 居中;
*/

span {
	display: block;
	overflow: hidden;
	padding-left: 5px;
	vertical-align: middle;
}

/*翻译
搜索栏框架样式 {
框阴影︰ 0 0 18px rgba(70,70,40,.255);括号里的颜色为Rgb默认，可进入http://rgb.phpddt.com/查询
-webkit 动画︰ fadeIn 2.5;
动画︰ fadeIn 2.5;
背景色︰ rgba(255,255,255,.100);
边界半径︰ 50px;
显示︰ 表;
垂直对齐︰ 居中;
宽度︰ 80%;根据你喜欢的宽度调整，目前我为了对齐图标使用80%
高度︰ 40px;
最大宽度︰ 400px;
边距︰ 10px 默认布局;
}
*/

.search_bar {
	box-shadow: 0 0 18px rgba(70,70,40,.255);
	-webkit-animation: fadeIn 2.5s;
	animation: fadeIn 2.5s;
	background-color: rgba(255,255,255,.100);
	border-radius: 50px;
	display: table;
	vertical-align: middle;
	width: 80%;
	height: 40px;
	max-width: 400px;
	margin: 10px auto;
}

/*翻译
搜索栏搜索目标确认图标样式，目前为米奇
轮廓边框︰ 0;
高度︰ 40px;
浮标位置︰ 右;
颜色: #000;
字体大小︰ 16px;
字体粗细︰ 700;
边境︰ 无;
背景颜色︰ 透明;
填充︰ 0 13px 0 13px
*/

#search_submit {
	outline: 0;
	height: 40px;
	float: right;
	color: #000;
	font-size: 16px;
	font-weight: 700;
	border: none;
	background-color: transparent;
	padding: 0 13px 0 13px
}

/*翻译
书签图标排版目录样式 
宽度︰ 100%;
文本对齐︰ 中心;
填充顶部︰ 15px;
填充底部︰ 15px;
*/

#content {
	width: 100%;
	text-align: center;
	padding-top: 15px;
	padding-bottom: 15px;
}

/*翻译
书签框架样式
-webkit 动画︰ fadeInDown 1s;
动画︰ fadeInDown 1s;
位置︰ 相对应;
显示︰ 显示在内部;
宽度︰ 75px;
边境︰ 0;
*/

.box {
	-webkit-animation: fadeInDown 1s;
	animation: fadeInDown 1s;
	position: relative;
	display: inline-block;
	width: 75px;
	border: 0;
}


/*翻译
书签图标样式
宽度︰ 100%;
高度︰ 100%;
位置︰ 不受限制;
左︰ 0;
顶︰ 0;
*/

.box a {
	width: 100%;
	height: 100%;
	position: absolute;
	left: 0;
	top: 0;
}

/*翻译
书签字体样式
颜色: #232323;使用夜间模式时修改为#eee或者#f2eada即可
高度︰ 1.5em;
线的高度︰ 1.5em;
宽度︰ 72px;
字体大小︰ 0.75em;
白色空间︰ nowrap;
溢出︰ 隐藏;
边距︰ 默认布局;
-webkit 边框顶部右半径︰ 5px;
-webkit 边框底部右半径︰ 5px;
文本溢出︰ 省略;
-o 文本溢出︰ 省略;
气相色谱-质谱-文本-溢出︰ 省略;
填充顶部︰ 3px;
填充底部︰ 8px;
*/

.url {
	color: #232323;
	height: 1.5em;
	line-height: 1.5em;
	width: 72px;
	font-size: 0.75em;
	white-space: nowrap;
	overflow: hidden;
	margin: auto;
	-webkit-border-top-right-radius: 5px;
	-webkit-border-bottom-right-radius: 5px;
	text-overflow: ellipsis;
	-o-text-overflow: ellipsis;
	-ms-text-overflow: ellipsis;
	padding-top: 3px;
	padding-bottom: 8px;
}

/*翻译
字体样式 
宽度︰ 3em;
高度︰ 3em;
最大宽度︰ 72px;
*/

.icon {
	width: 3em;
	height: 3em;
	max-width: 72px;
}


.main {
	margin: 10px;
	margin-top: -10px;
}


/*
下方为动画样式，不懂的不要修改
*/

@-webkit-keyframes flipInX {
	0% {
		-webkit-transform: perspective(400px) rotateX(90deg);
		transform: perspective(400px) rotateX(90deg);
		opacity: 0
	}

	40% {
		-webkit-transform: perspective(400px) rotateX(-10deg);
		transform: perspective(400px) rotateX(-10deg)
	}

	70% {
		-webkit-transform: perspective(400px) rotateX(10deg);
		transform: perspective(400px) rotateX(10deg)
	}

	100% {
		-webkit-transform: perspective(400px) rotateX(0);
		transform: perspective(400px) rotateX(0);
		opacity: 1
	}
}

@keyframes flipInX {
	0% {
		-webkit-transform: perspective(400px) rotateX(90deg);
		-ms-transform: perspective(400px) rotateX(90deg);
		transform: perspective(400px) rotateX(90deg);
		opacity: 0
	}

	40% {
		-webkit-transform: perspective(400px) rotateX(-10deg);
		-ms-transform: perspective(400px) rotateX(-10deg);
		transform: perspective(400px) rotateX(-10deg)
	}

	70% {
		-webkit-transform: perspective(400px) rotateX(10deg);
		-ms-transform: perspective(400px) rotateX(10deg);
		transform: perspective(400px) rotateX(10deg)
	}

	100% {
		-webkit-transform: perspective(400px) rotateX(0);
		-ms-transform: perspective(400px) rotateX(0);
		transform: perspective(400px) rotateX(0);
		opacity: 1
	}
}

@-webkit-keyframes fadeIn {
	0% {
		opacity: 0
	}

	100% {
		opacity: 1
	}
}

@keyframes fadeIn {
	0% {
		opacity: 0
	}

	100% {
		opacity: 1
	}
}

@-webkit-keyframes fadeInDown {
	0% {
		opacity: 0;
		-webkit-transform: translateY(-20px);
		transform: translateY(-20px)
	}

	100% {
		opacity: 1;
		-webkit-transform: translateY(0);
		transform: translateY(0)
	}
}

@keyframes fadeInDown {
	0% {
		opacity: 0;
		-webkit-transform: translateY(-20px);
		-ms-transform: translateY(-20px);
		transform: translateY(-20px)
	}

	100% {
		opacity: 1;
		-webkit-transform: translateY(0);
		-ms-transform: translateY(0);
		transform: translateY(0)
	}
}
</style>

<body>
<div id="content">
<br />
<div class="search_part">
<img class="smaller" src="logo/icon.png"></img>
</a>
<br />
<form href='javascript:void(0);' onsubmit="search();return false;" class="search_bar">
<input type="submit" id="search_submit" value="" >
<span><input class="search" type="text" value="" autocomplete="off" id="search_input" ></span>
</form>
</div>
<br />

<div class="main" >

<div class="box">
<a href="
https://www.google.com"></a>
<p><img class="icon" src="img/google.png" ></p>
<p class="url">Google</p>
</div>

<div class="box">
<a href="https://www.baidu.com"></a>
<p><img class="icon" src="img/bd.png" ></p>
<p class="url">百度</p>
</div>

<div class="box">
<a href="https://www.taobao.com"></a>
<p><img class="icon" src="img/tb.png" ></p>
<p class="url">淘宝</p>
</div>

<div class="box">
<a href="http://www.qq.com/"></a>
<p><img class="icon" src="img/txxw.png" ></p>
<p class="url">腾讯新闻</p>
</div>

<div class="box">
<a href="http://www.jd.com/"></a>
<p><img class="icon" src="img/jd.png" ></p>
<p class="url">京东</p>
</div>


<div class="box">
<a href="https://music.163.com/"></a>
<p><img class="icon" src="img/wyyyy.png" ></p>
<p class="url">网易云</p>
</div>

<div class="box">
<a href="https://www.zhihu.com/"></a>
<p><img class="icon" src="img/zh.png" ></p>
<p class="url">知乎</p>
</div>

<div class="box">
<a href="https://www.tmall.com/"></a>
<p><img class="icon" src="img/tm.png" ></p>
<p class="url">天猫</p>
</div>

<div class="box">
<a href="https://www.coolapk.com/"></a>
<p><img class="icon" src="img/ka.png" ></p>
<p class="url">酷安</p>
</div>

<div class="box">
<a href="http://bbs.zhiyoo.com/"></a>
<p><img class="icon" src="img/zy.png" ></p>
<p class="url">智友</p>
</div>

<div class="box">
<a href="http://www.appchina.com/"></a>
<p><img class="icon" src="img/yyh.png" ></p>
<p class="url">应用汇</p>
</div>

<div class="box">
<a href="https://www.so.com/"></a>
<p><img class="icon" src="img/360dh.png" ></p>
<p class="url">好搜</p>
</div>

<div class="box">
<a href="http://v.qq.com/"></a>
<p><img class="icon" src="img/txsp.png" ></p>
<p class="url">腾讯</p>
</div>

<div class="box">
<a href="http://www.iqiyi.com"></a>
<p><img class="icon" src="img/aqy.png" ></p>
<p class="url">爱奇艺</p>
</div>

<div class="box">
<a href="http://www.youku.com"></a>
<p><img class="icon" src="img/yksp.png" ></p>
<p class="url">优酷</p>
</div>

<div class="box">
<a href="https://tv.sohu.com/"></a>
<p><img class="icon" src="img/shsp.png" ></p>
<p class="url">搜狐</p>
</div>

</div>
<!--
如若要添加可复制一段
<div class="box">
<a href="地址"></a>
<p><img class="icon" src="img/icon6.png" ></p>
<p class="url">书签名称</p>
</div>
其中链接在href中如href="地址"建议填写folder://自己创建的文件夹地址，这样创建一次不必再修改
图标文件放置在img文件夹中定义如src="img/icon6.png"
显示的标题在<p class="url">书签名称</p>之间定义如<p class="url">酷安</p>
下方window.location.href =主页搜索引擎地址，目前为自用Pc版百度内部搜索，加上浏览器的顶部搜索即为双搜索，使用更方便

-->

</div>

<script type="text/javascript">
function search(){
if(document.getElementById("search_input").value != ""){
webview.search(document.getElementById("search_input").value);
document.getElementById("search_input").value = "";
}
return false;
}</script>

</body>
</html>
