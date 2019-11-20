<template>
	<div id="app">
		<div style="max-width: 100%">
			<div style="background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDMvNzIzNGQ1MjBkZjBiODhiMDIwYTc3ZmYwZjk1MGM3OGEuanBn.jpg'); background-repeat:no-repeat; background-size:cover; background-attachment:fixed; background-position:0 0%;height: 712px;">
				<banner></banner>

			</div>
			<div>
				<div style="max-width: 1365px;margin: 0 auto;">
					<div style="margin-top: 63px;text-align: center;">
						<div style="font-size: 30px;color: rgb(232, 76, 61;">您的创业梦想需要一个非同凡响的网站</div>
						<div style="color: rgb(105, 105, 105);margin-top: 40px;font-size: 20px;">云建站倾力打造的一个从网站建设.网网站运营管理到网站推广的自动化免费建站平台</div>
					</div>
					<div class="clearfix" style="height: 402px;text-align: center;overflow: hidden;">
						<div style="min-width: 1366px;">
							<div class="clearfix">
								<lee>

								</lee>
							</div>
						</div>
					</div>

				</div>
				<div style="height: 420px;background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvMWYyYjI0N2JjYTc5MjhkYzIyOTRiMjc0M2UyZDI1MWQuanBn.jpg'); background-repeat:no-repeat; background-size:cover; background-attachment:fixed; background-position:0 0%;">
					<div style="padding-top: 20px;padding-bottom: 29px;margin-top: 0;text-align: center;background-color: rgba(5,5,5,0.3);">
						<div style="font-size: 24px;color: #fff;margin:10px 0;">云建站自助平台</div>
						<div style="font-size: 24px;color: rgb(232, 76, 61);">上手快.颜值高.跨多屏.自传播.全免费.</div>
					</div>
					<div style="padding-top: 30px;box-sizing: border-box;">
						<div style="margin: 0 auto;max-width: 740px;text-align: center;color: #fff;font-size: 20px;line-height: 36px;">
							在起飞页自助建站平台，您不需要任何编程基础，就能做出功能强大，效果出众的专业级网站，您所要做的仅是选择网站模板、输入图片文字，以及鼠标拖拉拽；真正的响应式建站，无论是在电脑的大屏幕，还是手机小屏幕上，网站都能友好地展示；您的访客还可以注册成为会员，并进行在线购物；当然，如果您需要多语言版本，起飞页也可以轻松为您实现。</div>
					</div>
				</div>
				<div>
					<div style="margin-top: 63px;text-align: center;">
						<div style="font-size: 30px;color: rgb(232, 76, 61;">云建站，一站式的在线H5建站平台</div>
						<div style="color: rgb(105, 105, 105);margin-top: 40px;font-size: 20px;">云建站倾力打造的一个从网站建设.网网站运营管理到网站推广的自动化免费建站平台</div>
					</div>
					<div style="text-align:center ;margin-top: 35px;">
						<img style="760px;height: 646px;" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvNTE1Y2RhYTQxNDg0YWRiZDY4Mjg1NmU0OGNkZjFlYWYucG5n.png" />
					</div>
				</div>
				<div style="text-align:center;min-height: 724px;background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvMGIwYWIwZWU0YWRjNDQ5Yjg2YzFhZjMyOWNkZDc1MDYuanBn.jpg'); background-repeat:no-repeat; background-size:cover; background-attachment:fixed; background-position:0 0%;padding-top: 113px;padding-bottom: 145px;box-sizing: border-box;overflow: hidden;">
					<div style="max-width: 1280px;min-width: 1280px;height:466px;margin: 0 auto;">
						<div v-for="i in 8" style="float: left;margin:20px;margin-bottom: 40px;">
						<lee2>
							<div style="font-size: 16px;color: #d3d3d3;margin: 15px 0;" slot='ccc'>跨屏展示</div>
						</lee2>
					</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	import banner from './banner.vue'
	import lee from './lee.vue'
	import lee2 from './lee2.vue'

	export default {
		components: {
			banner,
			lee,
			lee2
		}
	}
</script>

<style>
	* {
		padding: 0;
		margin: 0;
	}
	
	.clearfix:after,
	.clearfix:before {
		content: "";
		display: table;
	}
	
	.clearfix:after {
		clear: both;
	}
	
	.clearfix {
		*zoom: 1;
	}
</style>