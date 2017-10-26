<template>
	<div>
		<div class="my-order">
			<p>我的订单</p>
			<div class="nav_box">
				<ul class="order_nav">
					<li>
						<a class="nav-item">全部</a>
					</li>
					<li>
						<a class="nav-item">待付款</a>
					</li>
					<li>
						<a class="nav-item">待发货</a>
					</li>
					<li>
						<a class="nav-item">待收货</a>
					</li>
					<li>
						<a class="nav-item">待评价</a>
					</li>
					<li>
						<a class="nav-item">退款/售后</a>
					</li>
					<li>
						<a class="nav-item">已完成/关闭</a>
					</li>
					<li>
						<a href="javascript:void(0)">订单回收站</a>
					</li>
				</ul>
			</div>
	
			<div class="order_list">
				<div class="list_tit">
					<p class="order_num">订单号:<span>150319690000</span></p>
					<p class="order_time">下单日期:<span>2015.04.09 18:06:06</span></p>
					<p class="shop_name">爱果果水果店</p>
					<p class="order_state">订单状态&nbsp;:&nbsp;<span>关闭</span></p>
				</div>
				<table>
					<tr>
						<td width="341" height="116"><img src="../../assets/account/goods1.png" /><span>赤小豆</span></td>
						<td width="92" height="116"><span>6个装</span></td>
						<td width="264" height="116"><span>¥16×1</span></td>
						<td rowspan="2" width="208" height="116">
							<h5>店铺合计:&nbsp;¥61</h5>
							<h5>(含运费:&nbsp;¥0)</h5>
						</td>
						<td rowspan="2" width="139" height="116">
							<a class="order_msg" href="javascript:void(0)">查看详情</a>
							<a href="javascript:void(0)">删除订单</a>
						</td>
					</tr>
					<tr>
						<td width="341" height="116"><img src="../../assets/account/goods1.png" /><span>赤小豆</span></td>
						<td width="92" height="116"><span>6个装</span></td>
						<td width="264" height="116"><span>¥16×1</span></td>
					</tr>
				</table>
	
			</div>
	
			<div class="order_list">
				<div class="list_tit">
					<p class="order_num">订单号:<span>150319690000</span></p>
					<p class="order_time">下单日期:<span>2015.04.09 18:06:06</span></p>
					<p class="shop_name">爱果果水果店</p>
					<p class="order_state">订单状态&nbsp;:&nbsp;<span>待付款</span></p>
				</div>
				<table>
					<tr>
						<td width="341" height="116"><img src="../../assets/account/goods1.png" /><span>赤小豆</span></td>
						<td width="92" height="116"><span>6个装</span></td>
						<td width="264" height="116"><span>¥16×1</span></td>
						<td rowspan="2" width="208" height="116">
							<h5>店铺合计:&nbsp;¥61</h5>
							<h5>(含运费:&nbsp;¥0)</h5>
						</td>
						<td rowspan="2" width="139" height="116">
							<a class="order_msg" href="javascript:void(0)">查看详情</a>
							<a href="javascript:void(0)">去支付</a>
							<a href="javascript:void(0)">取消订单</a>
						</td>
					</tr>
					<tr>
						<td width="341" height="116"><img src="../../assets/account/goods1.png" /><span>赤小豆</span></td>
						<td width="92" height="116"><span>6个装</span></td>
						<td width="264" height="116"><span>¥16×1</span></td>
					</tr>
				</table>
	
			</div>
			
			<div class="order_list">
				<div class="list_tit">
					<p class="order_num">订单号:<span>150319690000</span></p>
					<p class="order_time">下单日期:<span>2015.04.09 18:06:06</span></p>
					<p class="shop_name">爱果果水果店</p>
					<p class="order_state">订单状态&nbsp;:&nbsp;<span>待发货</span></p>
				</div>
				<table>
					<tr>
						<td width="341" height="116"><img src="../../assets/account/goods1.png" /><span>赤小豆</span></td>
						<td width="92" height="116"><span>6个装</span></td>
						<td width="264" height="116"><span>¥16×1</span></td>
						<td rowspan="2" width="208" height="116">
							<h5>店铺合计:&nbsp;¥61</h5>
							<h5>(含运费:&nbsp;¥0)</h5>
						</td>
						<td rowspan="2" width="139" height="116">
							<a class="order_msg" href="javascript:void(0)">查看详情</a>
							<a href="javascript:void(0)">申请退款</a>
						</td>
					</tr>
					<tr>
						<td width="341" height="116"><img src="../../assets/account/goods1.png" /><span>赤小豆</span></td>
						<td width="92" height="116"><span>6个装</span></td>
						<td width="264" height="116"><span>¥16×1</span></td>
					</tr>
				</table>
	
			</div>

		</div>
		
		
		
		
	</div>
	
</template>

<script>
	export default {
		name: "my-order",
		methods: {
			
		},
		data() {
			return {
				
			};
		},
		mounted(){
//			$(".order_msg").each(function () {
//				$(this).click(function () {
//					$(".my-order").css("display","none");
//					$(".zj-account-content").css("display","block");
//					$(".zj-nav .right").click(function () {
//						$(".zj-account-content").css("display","none");
//						$(".my-msg").css("display","block");
//						
//					})
//				})
//			})
		}
	}
</script>

<style scoped>
	.my-order {
		width: 1086px;
		border: 1px solid #e9e9e9;
		float: right;
		/*display: none;*/
	}
	
	.my-order p {
		width: 1066px;
		height: 57px;
		border-bottom: 1px solid #E9E9E9;
		font-size: 18px;
		font-family: "MicrosoftYaHei";
		color: rgb(51, 51, 51);
		line-height: 57px;
		padding-left: 20px;
	}
	
	.nav_box {
		display: flex;
		flex-direction: column;
		flex: 1;
	}
	
	ul,
	li {
		list-style: none;
	}
	
	a {
		text-decoration: underline;
	}
	
	.order_nav {
		display: flex;
	}
	
	.order_nav li {
		font-size: 16px;
		font-family: "MicrosoftYaHei";
		color: rgb(255, 255, 255);
		line-height: 28px;
		display: inline-block;
		padding: 0 20px;
		border-left: 2px solid #adadad;
		margin: 20px 0;
	}
	
	.order_nav li:nth-child(1) {
		border-left: 0;
	}
	
	.order_nav li:nth-child(8) {
		border-left: 0;
		margin-left: 66px;
	}
	
	.order_nav li:nth-child(1) a {
		background-color: #f08200;
		color: #fff;
	}
	
	.order_nav li:nth-child(8) a {
		color: #4b943d;
		text-decoration: underline;
	}
	
	.order_nav li a {
		color: #666;
		height: 28px;
		text-decoration: none;
		display: inline-block;
		padding: 0 14px;
		cursor: pointer;
	}
	/*.nav-item:link,
	.nav-item:visited {
		background-color: white;
		color: black;
	}*/
	
	.nav-item:hover,
	.nav-item:active {
		color: white;
		background-color: #f08200;
	}
	
	.order_list {
		width: 1044px;
		height: 286px;
		margin: auto;
	}
	
	.list_tit {
		width: 1042px;
		height: 46px;
		background-color: #f2f2f2;
		border: 1px solid #e9e9e9;
		border-bottom: 0;
	}
	
	.list_tit p {
		border: 0;
		font-size: 16px;
		font-family: "MicrosoftYaHei";
		color: rgb(51, 51, 51);
		line-height: 5;
		display: inline;
		line-height: 46px;
		margin-right: 30px;
	}
	
	.list_tit .shop_name {
		color: #4b943d;
	}
	
	.order_state {
		margin-left: 210px;
	}
	
	.order_state span {
		color: #f08200;
	}
	
	.order_list table {
		border: 1px solid #e9e9e9;
		border-collapse: collapse;
		font-size: 14px;
		font-family: "MicrosoftYaHei";
		color: rgb(102, 102, 102);
	}
	
	.order_list table td {
		padding: 0px 0 0 0px;
		position: relative;
		text-align: center;
	}
	
	.order_list table td img {
		position: absolute;
		top: 18px;
		left: 18px;
	}
	
	.order_list table td a {
		display: block;
		font-size: 14px;
		font-family: "MicrosoftYaHei";
		width: 90px;
		height: 30px;
		text-decoration: none;
		margin: 5px auto;
		border-radius: 4px;
		line-height: 30px;
	}
	
	.order_list table td a:nth-child(1) {
		color: #6ca861;
		text-decoration: underline;
	}
	
	.order_list table td a:nth-child(2) {
		color: #fff;
		background-color: #f08200;
	}
	
	.order_list table td a:nth-child(3) {
		color: #fff;
		background-color: #999;
	}
	
	.order_list table tr:first-child td:nth-child(4) {
		border-left: 1px solid #e9e9e9;
	}
	
	.order_list table tr:first-child td:nth-child(5) {
		border-left: 1px solid #e9e9e9;
	}
	
	.order_list table tr:first-child td:nth-child(1) {
		border-bottom: 1px solid #e9e9e9;
	}
	
	.order_list table tr:first-child td:nth-child(2) {
		border-bottom: 1px solid #e9e9e9;
	}
	
	.order_list table tr:first-child td:nth-child(3) {
		border-bottom: 1px solid #e9e9e9;
	}
	
	.block {
		text-align: center;
	}
	
	
	
	
</style>