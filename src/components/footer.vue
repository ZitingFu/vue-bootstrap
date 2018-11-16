<template>
  <div id="footer">
    <div class="fotter-bottom">
		<div class="left">
			<div style="width: 100%;height: 30px;">
				<img src="../assets/logo.png" alt="">
			</div>
			<p>我们一直致力于为广大开发者提供更多的优质技术文档和辅助开发工具！</p>
		</div>
		<div class="right">
			<table>
				<tr>
					<th>关于</th>
					<th>联系方式</th>
					<th>旗下网站</th>
					<th>赞助商</th>
				</tr>
				<tr>
					<td><a href="">关于我们</a></td>
					<td><a href="">新浪微博</a></td>
					<td><a href="">Laravel中文网</a></td>
					<td><a href="">猫云</a></td>
				</tr>
				<tr>
					<td><a href="">广告合作</a></td>
					<td><a href="">电子邮件</a></td>
					<td><a href="">Ghost中国</a></td>
					<td><a href="">京东云</a></td>
				</tr>
				<tr>
					<td><a href="">友情链接</a></td>
					<td><a href=""></a></td>
					<td><a href="">BootCDN</a></td>
					<td><a href="">又拍云</a></td>
				</tr>
				<tr>
					<td><a href="">招聘</a></td>
					<td><a href=""></a></td>
					<td><a href="">Packagist中国镜像</a></td>
					<td><a href=""></a></td>
				</tr>
				<tr>
					<td><a href=""></a></td>
					<td><a href=""></a></td>
					<td><a href="">燃腾教育</a></td>
					<td><a href=""></a></td>
				</tr>
			</table>
		</div>
    </div>
    <p class="p2">京ICP备11008151号<span></span>京公网安备11010802014853</p>
  </div>
</template>

<script>

export default {
  name: 'Footer'
}
</script>

<style scoped>
#footer{
	border-top:1px solid #ddd;
	margin-bottom:50px; 
}
.fotter-bottom{
	padding-top:40px; 
	color: #777;
	width:1170px;
	overflow:hidden;
	margin: 0 auto;
	font-size:12px; 
 	border-bottom:1px solid #ddd;
}
.left{
	float: left;
}
.right{
	float: right;
}
table a{
	color: #777;
	text-decoration: none;
}
table a:hover{
	text-decoration:underline;
}
table{
	text-align: left;
}
table th{
	font-size: 16px;
	width:127px;
	font-weight: normal;
	color: #563d7c;
	padding-bottom:8px; 
}
table td{
	font-size: 14px;
}
.p2{
	font-size: 14px;
	color: #777;
}
.p2 span{
	width: 1px;
	display: inline-block;
	height:16px;
	background-color: #ddd;
	margin:0 8px; 
}
img{
	float: left;
}
</style>
