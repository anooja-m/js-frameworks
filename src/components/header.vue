<template>
  
<nav>

		<ul>
			<li class="active"><a href="k.html">Home</a></li>
			<li><a href="#">About Us</a></li>
			<li><a href="#">Contact Us</a></li>
			<li><a href="#">Blog</a></li>
		</ul>
	</nav>
	 <h1 id="example">DEPARTMENT OF COMPUTER APPLICATIONS </h1>
	 <button type="button">EXPLORE</button>
</template>

<script>

</script>


<style scoped>
header{
	background:#8c0073;
	height: 100vh;
	background-size: cover;
	background-position: center;

}
ul{
	float: right;
}
		ul li {

			list-style-type: none;
		
		display: inline-block;
    margin-top: 5px;
    padding-top: 2%;
		}
		ul li a{
			display: inline-block;
			text-decoration: none;
    color: #fff;
    padding: 5px 10px;
    border: 1px solid transparent;
    transition: 0.6s ease;
    
		}
		ul li a:hover{
	background-color: #fff;
	color: #000;

}
 nav ul li.active a{
	background-color: #fff;
	color: #000;

}
h1{
color: #fff;
	font-size: 5vw;
	text-align: center;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%,-50%);
}
button{
	position: absolute;
	top: 75%;
	left: 50%;
	transform: translate(-50%,-50%);
border: 1px solid #fff;
	padding: 10px 10px;
	
	text-decoration: none;
	transition: 0.6s ease;
}
</style>
