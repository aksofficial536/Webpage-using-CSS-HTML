# Webpage-using-CSS-HTML
How to create a webpage using CSS & HTML. 
<!DOCTYPE html>
<html>
<head>
	<title>Web Page</title>
	<style >
		body{
			margin:0;
		}
		#header{
			width:100%;
			min-height:70px;
			background-color:green;
		}
		#middle{
			width:100%;
			min-height:480px;
			background-color:black;
			padding:5% 0;
		}
		#footer{
			width:100%;
			height:70px;
			background-color:black;
		}
		#logo{
			width:20%;
			height:70px;
			float:left;
		}
		#logo img{
			width:65%;
			float:left;
			margin:3% 15%;
		}
		#nav{
			width:70%;
			float:left;
			float:right;
		}
		.nav-links{
			text-decoration:none;
			color:white;
			font-weight:900;
			font-size:20px;
			margin:2% 5%;
			float:left;
		}
		.nav-links:hover{
			color:red;
		}
		#footer h2{
			color:white;
			text-align:center;
			padding-top:1%;
		}
		#bolg{
			width:70%;
			height:250px;
			background-color:blue;
			margin:3% auto;
		}
		#blog-image{
			width:40%;
			height:252px;
			background-color:green;
			float:left;
		}
		#bolg-content{
			width:60%;
			height:252px;
			background-color:red;
			float:left;
		}
		.bimg{
			width:100%;
		}
		#blog-title{
			color:white;
			margin:3% 5%;
		}
		#blog-dis{
			color:white;
			margin:3% 5%;
		}
	</style>
</head>
<body>
	<div id="header">
		<div id="logo">
			<img src="IMG_20180402_100503.png" />
		</div>
		<div id="nav">
			<a href="https://github.com/aksofficial536" class="nav-links">HOME</a>
			<a href="https://wordpress.com/stats/day/aksofficial536.home.blog" class="nav-links">Website</a>
			<a href="https://www.youtube.com/channel/UCBviNTuPflP2YRNnMnYr-Qw?view_as=subscriber" class="nav-links">Youtube</a>
		</div>
	</div>
	<div id="middle">
		<div id="blog">
			<div id="blog-image">
				<img src="IMG_20180402_100503.png" class="bimg" />
			</div>
			<div id="bolg-content">
				<h1 id="blog-title">
					This is My Blog.
				</h1>
				<p id="blog-dis">
					welome to my blog.
				</p>
			</div>
		</div>
		<div id="middle">
		<div id="blog">
			<div id="blog-image">
				<img src="IMG_20180402_100503.png" class="bimg" />
			</div>
			<div id="bolg-content">
				<h1 id="blog-title">
					This is My Blog.
				</h1>
				<p id="blog-dis">
					welome to my blog.
				</p>
			</div>
		</div>
	</div>
	<div id="footer">
		<h2>Copyright Reserved &copy;</h2>
	</div>
	</body>
</html>
