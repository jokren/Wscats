<template>
	<div>
		<div id="Sma-kfz-one">
			<img src="../../czimg/os-10.jpg" />
		</div>
		<div id="Sma-kfz-three">
			<img src="../../czimg/os-12.jpg" />
		</div>
		<div id="Sma-kfz-five">
			<img src="../../czimg/os-14.jpg" />
		</div>
		<div id="Sma-kfz-six">
			<img src="../../czimg/os-15.jpg" />
		</div>
		<div id="Sma-kfz-seven">
			<img src="../../czimg/os-16.jpg" />
		</div>
		
		<div id="Sma-kfz-slide">
			<el-collapse v-model="activeNames" @change="handleChange">
				<el-collapse-item title="订单服务 " name="1">
					<div><a href="https://www.smartisan.com/support/#/help-service/instruction">购买指南</a></div>
					<div><a href="https://www.smartisan.com/support/#/help-service/payment">支付方式</a></div>
					<div><a href="https://www.smartisan.com/support/#/help-service/delivery">送货政策</a></div>
				</el-collapse-item>
				<el-collapse-item title="服务支持" name="2">
					<div>售货服务</div>
					<div>售货政策</div>
					<div>保修服务</div>
					<div>维修报价</div>
					<div>维修门店</div>
					<div>零售门店</div>
				</el-collapse-item>
				<el-collapse-item title="自助服务" name="3">
					<div>热点资讯</div>
					<div>预约购买</div>
					<div>订单物流</div>
					<div>日常使用</div>
					<div>常见问题</div>
				</el-collapse-item>
				<el-collapse-item title="媒体中心" name="4">
					<div>新闻动态</div>
					<div>官方视频</div>
					<div>图片资源</div>
					<div>时尚之选</div>
				</el-collapse-item>
				<el-collapse-item title="关于公司" name="5">
					<div>公司简介</div>
					<div>获奖信息</div>
					<div>企业文化</div>
					<div>加入我们</div>
					<div>联系我们</div>
				</el-collapse-item>
				<el-collapse-item title="关注我们" name="6">
					<div><a href="https://weibo.com/smartisan">新浪微博</a></div>
					<div>官方微博</div>
					<div><a href="http://tieba.baidu.com/f?kw=%B4%B8%D7%D3%BF%C6%BC%BC">官方之贴</a></div>
				</el-collapse-item>
			</el-collapse>
		</div>
		<div id="Sma-kfz-footer">
			<div>
				<p>Copyright © 2018, Smartisan Digital Co., Ltd. All Rights Reserved.</p>
			</div>
			<div class="Sma-kfz-one">
				<h6>北京锤子数码科技有限公司</h6>
				<ul>
					<li>
						<a href="#">法律声明</a>
					</li>
					<li>
						<a href="#">隐私条款</a>
					</li>
				</ul>
			</div><br />
			<div class="Sma-kfz-two">
				<i>京ICP备14041720号-1 京ICP证140622号 京公网安备11010502025474</i>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				activeNames: []
			};
		},
		methods: {
			handleChange(val) {
				console.log(val);
			}
		}
	}
</script>

<style scoped>
	#Sma-kfz-one img {
		width: 100%;
		height: 3.90rem;
	}
	
	#Sma-kfz-three img {
		width: 100%;
		height: 2.42rem;
	}
	
	#Sma-kfz-five img {
		width: 100%;
		height: 3.89rem;
	}
	
	#Sma-kfz-six img {
		width: 100%;
		height: 3.5rem;
	}
	
	#Sma-kfz-seven img {
		width: 100%;
		height: 4.06rem;
	}

	
	#Sma-kfz-slide .haode:nth-child(1) {
		border-top: 1px solid #e8e4e4;
	}
	
	#Sma-kfz-slide .haode {
		padding-left: 0.3rem;
		border-bottom: 1px solid #e8e4e4;
	}
	
	#Sma-kfz-footer {
		height: 0.81rem;
		width: 100%;
	}
	
	#Sma-kfz-footer h5 {
		float: left;
		padding: 0 0.1rem
	}
	
	#Sma-kfz-footer .privacy li {
		float: left;
		padding: 0 0.1rem;
		border-left: 1px solid #ccc;
		text-align: center;
	}
	
	#Sma-kfz-footer .privacy li a {
		color: blue;
	}
	
	#Sma-kfz-footer p {
		margin-top: 0.15rem;
	}
	
	#Sma-kfz-footer .Sma-kfz-one {
		margin-top: 0.15rem;
	}
	
	#Sma-kfz-footer .Sma-kfz-one h6 {
		float: left;
		padding: 0 0.1rem 0 0.6rem;
	}
	
	#Sma-kfz-footer .Sma-kfz-one ul li {
		float: left;
		padding: 0 0.1rem;
		border-left: 1px solid #ccc;
	}
	
	#Sma-kfz-footer .Sma-kfz-one ul li a {
		color: #0000FF;
	}
	
	#Sma-kfz-footer .Sma-kfz-two {
		text-align: center;
		padding-top: 0.08rem;
	}
</style>