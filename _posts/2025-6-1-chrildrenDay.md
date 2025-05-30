layout: post
title: 儿童节快乐
---
<style>
  .mr-cont{
	height:500px;
	width:800px;
	margin: 0 auto;
	position: relative;
	background: url(images/bg.jpg)
  }
  .go{
	position: absolute;
	top:80px;
	left: 120px;
	height: 200px;
	z-index: 50;
  }
  .go:hover  {
	transform:rotate(1080deg);
	transition:2s all ease-out;
	transform-origin:50% 49%;	
  }
  .bar{
	position: absolute;
	top:220px;
	left: 180px;
	z-index: 0;
	transform:rotate(29deg);
  }
  
</style>
<div class="mr-cont">
    <img src="images/pic1.png" alt="" class="go">
    <img src="images/bar.png" alt="" class="bar">
</div>
