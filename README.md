﻿<style>
/*灵感来源于创作*/
body,ul,li{margin:0;padding:0;}
a{ text-decoration: none;color:#FB94A6;font-size:14px;}
ul{list-style:none;margin:0 auto;display:block;width:650px;margin-top:100px;}
ul li{float:left;display:inline;}
ul li a{padding:10px 30px;border:1px dashed pink;text-align:center;display:block;}
ul li a:hover{background:#F8BFC9;border:1px dashed #FB94A6;color:#fff;}
.menu{visibility:hidden;width:0px;margin:0;}
ul li:hover ul{visibility:visible;}
/*
visibility:hidden; visibility:visible; 可以换成
display:none; display:block;
*/
</style>

<ul>
 <li><a href="#">Demo</a></li>
 <li><a href="#">Demo</a>
 	<ul class="menu">
 	<li><a href="#">Demo</a></li>
 	<li><a href="#">Demo</a></li>
 	<li><a href="#">Demo</a>
 	</li>
 	</ul>
 </li>
 <li><a href="#">Demo</a></li>
 <li><a href="#">Demo</a></li>
 <li><a href="#">Demo</a>
 	<ul class="menu">
 	<li><a href="#">Demo</a></li>
 	<li><a href="#">Demo</a></li>
 	<li><a href="#">Demo</a></li>
 	</ul>
</li>
 </ul>