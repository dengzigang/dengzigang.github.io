<template>
	<div id="app">
		<div class="header">
			<div class="container">
				<div class="h_center">
					<div class="c_top">
						<h1>起飞页自助建站平台</h1>
					</div>
					<div style="margin-top: 42px;">
						<div class="c_center">
							<ul>
								<li>与创业为伴,点亮创新,<span>是云建站的使命.</span></li>
								<li>与创业为伴,点亮创新,是云建站的使命.</li>
								<li>与创业为伴,点亮创新,是云建站的使命.</li>
								<li>与创业为伴,点亮创新,是云建站的使命.</li>
							</ul>
						</div>
					</div>
					<div>
						<div class="c_bottom" style="overflow: hidden;">
							<div style="text-align: center;">
								<span>自助建站平台</span>
							</div>
							<div class="c_xia">
								<ul v-for="i in arr">
									<li><img :src="i.img" /></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				arr: [
					{
						img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvYjgxZjYwZjI5NWFlMzgzODExMzliNDU2ZTkwMGUyYTEtNDd4NDcucG5n.png'
					},
					{
						img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvODUyMjA2ZWViZDZiMmY0YjU1ZjkwZGI3MjNhODRjNWMtNDd4NDcucG5n.png'
					},
					{
						img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZjU4N2RiMTkzOWE0YjI4NTk0NzA3MjFjYTJhZTYwMDAtNDd4NDcucG5n.png'
					},
					{
						img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvOWIxMTg4ODYwZDI4MzE0MTlmNjkyZjJhM2Y5ZTY5OGUtNDd4NDcucG5n.png'
					},
					{
						img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZDczNTgwOTlmZWEzN2UyY2E4YTVjZWVjNmIxMDU4NmUtNDd4NDcucG5n.png'
					},
					{
						img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZjcxMDlkMGU1YmUwZWQ1MjA5ZTk0YjFlYjMwMzY3YjYtNDd4NDcucG5n.png'
					},
				]
			}
		}
	}
</script>

<style>
	* {
		margin: 0;
		padding: 0;
		list-style: none;
	}
	.header {
		width: 100%;
		background: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDMvNzIzNGQ1MjBkZjBiODhiMDIwYTc3ZmYwZjk1MGM3OGEuanBn.jpg');
		padding-top: 60px;
		padding-bottom: 81px;
	}
	
	.h_center {
		padding: 0 40px;
		padding-top: 162px;
	}
	
	.c_top {
		margin: 0 auto;
		min-width: 700px;
	}
	
	.c_top h1 {
		font-size: 60px;
		font-weight: normal;
		font-style: normal;
		color: #ffffff;
		text-align: center;
	}
	
	.c_center {
		max-width: 750px;
		margin: 0 auto;
		border-top: 2px solid #c9c9c9;
		border-bottom: 2px solid #c9c9c9;
		border-left: 0px solid #c9c9c9;
		border-right: 0px solid #c9c9c9;
	}
	
	.c_center ul {
		color: #333;
		font-size: 36px;
		overflow: hidden;
		height: 100px;
		line-height: 100px;
		white-space: nowrap;
		text-overflow: ellipsis;
	}
	
	.c_center ul li {
		color: #FFFFFF;
		text-align: center;
	}
	
	.c_center ul li span {
		color: red;
	}
	
	.c_bottom {
		margin-top: 56px;
		min-width: 700px;
	}
	
	.c_bottom span {
		font-size: 26px;
		color: #FFFFFF;
		font-family: 微软雅黑体;
	}
	
	.c_xia {
		width: 380px;
		padding-top: 25px;
		overflow: hidden;
		margin: 0 auto;
	}
	
	.c_xia ul {
		float: left;
		margin-right: 16px;
	}
</style>