<template>
	<div class="account">
		<div class="account_count">
			<div class="account_up">
				<div class="up_pic">
					<img src="../../assets/account/lemon.png" />
				</div>
				<p class="hello">您好,<span>135****2365</span></p>
				<div class="up_leiBox">
					<div class="up_lei"><span>当前积分</span><span>125</span></div>
					<div class="up_lei"><span>我的钱包</span><span>¥1220.0</span></div>
					<div class="up_lei">
						<span><router-link to="/user/wallet">充值有礼>></router-link></span>
						<span><router-link class="exchange" href="###">充值卡兑换</router-link>>></span>
					</div>
				</div>
			</div>
			<div class="account_down">
				<div class="down_box">
					<div class="box_box">
						<p>新人福利享不停</p>
						<p>充值有好礼</p>
					</div>
				</div>
			</div>
		</div>
		
		<!--充值卡兑换-->
		<div class="zj-account-content">
			<div class="zj-nav">
				<span class="left">充值卡兑换</span>
				<span class="right">查看账单</span>
			</div>
			<div class="card_cont">
				<input type="text" placeholder="请输入充值卡兑换码进行充值" />
				<button>充值</button>
			</div>
			
		</div>
		
		
		<!--我的消息-账单-->
		<div class="my-msg">
			<p>我的消息</p>
			<div class="jifen">
				<ul class="all_msg">
					<li>
						<span>操作</span>
						<span>充值金额</span>
						<span>账户余额</span>
						<span>时间</span>
					</li>
					<li>
						<span>充值</span>
						<span>+¥1000.00元</span>
						<span>¥3443.03元</span>
						<span>2015-04-15 17:21:21</span>
					</li>
					<li>
						<span>消费</span>
						<span>-¥1000.00元</span>
						<span>¥3443.03元</span>
						<span>2015-04-15 17:21:21</span>
					</li>
					<li>
						<span>退款</span>
						<span>+¥1000.00元</span>
						<span>¥3443.03元</span>
						<span>2015-04-15 17:21:21</span>
					</li>
				</ul>
			</div>
		</div>
		
	</div>
</template>

<script>
	export default {
		name: "account",
		data() {
			return {

			}
		},
		mounted(){
				$(".exchange").click(function () {
					$(".account_count").css("display","none");
					$(".zj-account-content").css("display","block");
					$(".zj-nav .right").click(function () {
						$(".zj-account-content").css("display","none");
						$(".my-msg").css("display","block");
						
					})
				})
		}
	}
</script>

<style scoped>
	.account_count {
		width: 1085px;
		height: 625px;
		position: absolute;
		top: 0;
		left: 195px;
	}
	
	.account_up {
		width: 1083px;
		height: 219px;
		border: 1px solid #E7E7E7;
		background-color: #f4fff2;
		position: relative;
	}
	
	.account_down {
		width: 1085px;
		height: 382px;
		border: 1px/*solid*/
		#E7E7E7;
		margin-top: 20px;
		background: url(../../assets/account/acc_down.png) no-repeat;
		background-size: 100% 100%;
		overflow: hidden;
		cursor: pointer;
	}
	
	.up_pic {
		width: 140px;
		height: 140px;
		background-color: #ffe313;
		border-radius: 50%;
		margin: 40px;
	}
	
	.up_pic img {
		padding: 5px 5px;
	}
	
	.account_up .hello {
		width: 380px;
		font-size: 18px;
		font-family: "MicrosoftYaHei";
		color: rgb(102, 102, 102);
		line-height: 219px;
		margin: 0;
		padding: 0;
		position: absolute;
		left: 220px;
		top: 0;
	}
	
	.hello span {
		color: #e85e35;
	}
	
	.up_leiBox {
		width: 480px;
		height: 219px;
		position: absolute;
		top: 0;
		right: 0;
	}
	
	.up_leiBox .up_lei:nth-child(3) span:nth-child(1) a{
		color: #4b943d;
	}
	
	.up_lei {
		width: 152px;
		float: left;
		margin-top: 60px;
	}
	
	.up_lei span {
		display: inline-block;
		font-size: 18px;
		font-family: "MicrosoftYaHei";
		color: rgb(37, 37, 37);
		line-height: 2.667;
		width: 152px;
	}
	
	.up_lei span:nth-child(2),a {
		color: #e85e35;
	}
	
	.up_lei span a{
		text-decoration: none;
	}
	
	.down_box {
		background-color: rgba(255, 255, 255, 0.302);
		width: 537px;
		height: 234px;
		margin: 87px auto;
		overflow: hidden;
	}
	
	.box_box {
		background-color: rgba(255, 255, 255, 0.302);
		opacity: ;
		width: 517px;
		height: 214px;
		margin: 10px auto;
	}
	
	.box_box p {
		display: block;
		margin: auto;
	}
	
	.box_box p:nth-child(1) {
		/*width: 420px;*/
		font-size: 48px;
		font-family: "MicrosoftYaHei";
		color: rgb(255, 255, 255);
		font-weight: bold;
		line-height: 110px;
		text-align: center;
		text-shadow: 0px 3px 5px rgba(0, 0, 0, 0.31);
		letter-spacing: 13px;
	}
	
	.box_box p:nth-child(2) {
		width: 420px;
		height: 68px;
		font-size: 36px;
		font-family: "MicrosoftYaHei";
		color: rgb(255, 255, 255);
		font-weight: bold;
		line-height: 68px;
		text-align: center;
		text-shadow: 0px 3px 5px rgba(0, 0, 0, 0.31);
		border-bottom: 1px solid white;
		border-top: 1px solid white;
		letter-spacing: 34px;
	}
	
	.zj-account-content{
		border: 1px solid #e9e9e9;
		width: 1083px;
		height: 623px;
		float: right;
		display: none;
	}
	.zj-account-content .zj-nav{
		border-bottom: 1px solid #e9e9e9;
		height: 57px;
		font-size: 17px;
		
		color: #252525;
	}
	.zj-account-content .zj-nav .left{
		margin-left: 20px;
		line-height: 57px;
	}
	.zj-account-content .zj-nav .right{
		display: inline-block;
		width: 70px;
		height: 30px;
		border-radius: 5px;
		color: white;
		font-size: 14px;
		background-color: #498e3d;
		line-height: 30px;
		padding:0 10px 0 10px;
		float: right;
		margin-right: 20px;
		margin-top: 13px;
		text-align: center;
	}
	
	.card_cont{
		margin: 51px 0 0 31px;
	}
	
	.card_cont input{
		width: 475px;
		height: 50px;
		padding-left: 20px;
		display: block;
		margin-bottom: 100px;
		font-size: 18px;
		border: 1px solid #e8e8e8;
	}
	input::-webkit-input-placeholder{ 
		color: #999; 
	} 
	
	.card_cont button{
		border-radius: 5px;
		background-color: rgb(240, 130, 0);
		width: 150px;
		height: 50px;
		border: 0;
		outline: none;
		font-size: 20px;
		font-family: "MicrosoftYaHei";
		color: rgb(255, 255, 255);
		line-height: 50px;
		display: block;
	}
	
	.my-msg {
		width: 1083px;
		height: 622px;
		border: 1px solid #e9e9e9;
		position: absolute;
		top: 0;
		left: 195px;
		display: none;
	}
	
	.my-msg p {
		width: 1083px;
		height: 57px;
		border-bottom: 1px solid #E9E9E9;
		font-size: 18px;
		color: rgb(51, 51, 51);
		line-height: 57px;
		padding-left: 20px;
	}
	
	
	.jifen {
		margin: 20px 0 0 20px;
	}
	
	.jifen ul {
		width: 1042px;
		border: 1px solid #e9e9e9;
		border-bottom: 0;
	}
	
	.jifen ul li {
		border-bottom: 1px solid #e9e9e9;
		height: 53px;
		line-height: 53px;
	}
	
	.jifen ul li:nth-child(1) {
		background-color: #f2f2f2;
		border-bottom: 0;
		height: 46px;
		line-height: 46px;
	}
	
	.jifen li:hover {
		background-color: #f4fff2;
	}
	
	.jifen li span {
		width: 24%;
		display: inline-block;
		text-align: center;
		font-size: 14px;
		color: rgb(102, 102, 102);
	}
	.all_msg li span:nth-child(3){
		color: #f29322;
	}
	.all_msg li:nth-child(1) span:nth-child(3){
		color: rgb(102, 102, 102);
	}
</style>