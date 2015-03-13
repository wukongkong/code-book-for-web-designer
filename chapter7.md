第七章 浅说表单
===

先说什么是表单，就是我们平时在网上注册啊，登陆啊，搜索啊，这些行为用到都是表单。我们输入一些数据，然后提交给服务器，让服务器去处理数据。那么收集数据的这部分面向用户的代码就是表单。

先玩个简单的哦~

	<form action="http://cn.bing.com/search" method="get">
		<input type="text" name="q">
		<button type="submit">点此搜索</button>
	</form>

form 是表单，

> action 属性表示数据提交给哪个地址
> method 表示数据提交的方法，有 get 和 post 两种类型

input 是用来输入的区域，

> type 类型，用来指定这个输入区域的类型，比如文本啊，数字啊
> name 给这个输入域获得数值取个名字，要不然很多输入框什么的怎么区分啊

button 按钮

> submit 这个类型很特殊，是提交表单的意思，也就是按了这个类型的按钮之后整个表单的数据就会发送出去。

好像就明白了，你可以试试这个代码的效果，嗯，这个办法可以很容易地给我们的网站添加搜索功能，进而的我们想想那些所谓的多重搜索的网站可能也不过尔尔。

当然事实上表单还有很多玩法，也能玩出各种花样，不过这些等我们后面研究 JavaScript 的时候再说了。