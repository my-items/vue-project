<template>
	<div class="movie_body">
		<ul>
			<li>
				<div class="pic_show"><img src="../../assets/images/movie_1.jpg" ></div>
				<div class="info_list">
					<h2>毒液：致命守护者</h2>
					<p>观众评分 <span class="grade">9.2</span></p>
					<p>主演: 黄渤、张译、吴京、杜江等</p>
					<p>今天82家影院放映576场</p>
				</div>
				<div class="btn_pre">预售</div>
			</li>
			<li>
				<div class="pic_show"><img src="../../assets/images/movie_2.jpg" ></div>
				<div class="info_list">
					<h2>无名之辈</h2>
					<p>观众评分 <span class="grade">8.4</span></p>
					<p>主演: 于和伟、吴磊、张子枫</p>
					<p>今天82家影院放映576场</p>
				</div>
				<div class="btn_pre">购票</div>
			</li>
		</ul>
	</div>
</template>

<script>
	export default{
		name : 'ComingSoon'
	}
</script>

<style scoped>
	#content .movie_body {
		flex: 1;
		overflow: auto;
	}
	
	.movie_body ul {
		margin: 0 12px;
		overflow: hidden;
	}
	
	.movie_body ul li {
		margin-top: 12px;
		display: flex;
		align-items: center;
		border-bottom: 1px solid #E6E6E6;
		padding-bottom: 10px;
	}
	
	.movie_body .pic_show {
		width: 64px;
		height: 90px;
	}
	
	.movie_body .pic_show img {
		width: 100%;
	}
	
	.movie_body .info_list {
		margin-left: 10px;
		flex: 1;
		position: relative;
	}
	
	.movie_body .info_list h2 {
		font-size: 17px;
		line-height: 24px;
		width: 150px;
		overflow: hidden;
		white-space: nowrap;
		text-overflow: ellipsis;
	}
	
	.movie_body .info_list p {
		font-size: 13px;
		color: #666;
		line-height: 22px;
		width: 200px;
		overflow: hidden;
		white-space: nowrap;
		text-overflow: ellipsis;
	}
	
	.movie_body .info_list .grade {
		font-size: 15px;
		font-weight: 700;
		color: #faaf00;
	}
	
	.movie_body .info_list img {
		width: 50px;
		position: absolute;
		right: 10px;
		top: 5px;
	}
	
	.movie_body .btn_mall,
	.movie_body .btn_pre {
		width: 47px;
		height: 27px;
		line-height: 28px;
		text-align: center;
		background-color: #f03d37;
		color: #fff;
		border-radius: 4px;
		font-size: 12px;
		cursor: pointer;
	}
	
	.movie_body .btn_pre {
		background-color: #3c9fe6;
	}
	
	.movie_body .pullDown {
		margin: 0;
		padding: 0;
		border: none;
	}
</style>
