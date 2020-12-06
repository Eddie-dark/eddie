# eddie
dark
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>扑克</title>
	<style>
    .puke{
       position: relative;
       margin-top:10%;
       left: 40%;
       width: 400px;
       height: 613px;
    }
    img{
    	width: 400px;
        height: 613px;
        transition: all 1s linear;
    	position: absolute;
    	transform-origin:center bottom;
    }
    .puke:hover img:nth-child(1){
    	transform: rotate(-47deg);
    	backface-visibility: hidden;
    	
    }
    .puke:hover img:nth-child(2){
    	transform: rotate(-39deg);
    	
    }
    .puke:hover img:nth-child(3){
    	transform: rotate(-31deg);
    	
    }
    .puke:hover img:nth-child(4){
    	transform: rotate(-23deg);
    	
    }
    .puke:hover img:nth-child(5){
    	transform: rotate(-15deg);
    	
    }
    .puke:hover img:nth-child(6){
    	transform: rotate(-7deg);
    	
    }
    .puke:hover img:nth-child(7){
    	transform: rotate(1deg);
    	
    }
    .puke:hover img:nth-child(8){
    	transform: rotate(9deg);
    	
    }
    .puke:hover img:nth-child(9){
    	transform: rotate(17deg);
    	
    }
    .puke:hover img:nth-child(10){
    	transform: rotate(25deg);
    	
    }
    .puke:hover img:nth-child(11){
    	transform: rotate(33deg);
    	
    }
    .puke:hover img:nth-child(12){
    	transform: rotate(41deg);
    	
    }
    .puke:hover img:nth-child(13){
    	transform: rotate(49deg);
    	
    }
    .puke:hover img:nth-child(14){
    	transform: rotate(57deg);
    	
    }
    .puke:hover img:nth-child(15){
    	transform: rotate(65deg);
    	
    }
    
    

	</style>
</head>
<body>
	<div class="puke">
		<img src="images/1.jpg" alt="">
		<img src="images/2.jpg" alt="">
		<img src="images/3.jpg" alt="">
		<img src="images/4.jpg" alt="">
		<img src="images/5.jpg" alt="">
		<img src="images/6.jpg" alt="">
		<img src="images/7.jpg" alt="">
		<img src="images/8.jpg" alt="">
		<img src="images/9.jpg" alt="">
		<img src="images/10.jpg" alt="">
		<img src="images/11.jpg" alt="">
		<img src="images/12.jpg" alt="">
		<img src="images/13.jpg" alt="">
		<img src="images/j.jpg" alt="">
		<img src="images/j2.jpg" alt="">
	</div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>盾牌</title>
	<style type="text/css">
	html,body{
        height: 100%;
    }
    body{
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: green;
    }
    .shield{
        width: 440px;
        margin:0 auto;
        margin-top: 10%;
    }
    .shield img {
        transition: all 1s linear;
    }
    img:nth-child(1){
        transform: translate(-50px,40px) rotate(180deg);
    }
    img:nth-child(2){
        transform: translate(-150px,-120px) rotate(80deg);
    }
    img:nth-child(3){
        transform: translate(100px,-80px) rotate(70deg);
    }
    img:nth-child(4){
        transform: translate(-150px,10px) rotate(130deg);
    }
    img:nth-child(5){
        transform: translate(0,0) rotate(0deg);
    }
    img:nth-child(6){
        transform: translate(0px,00px) rotate(0deg);
    }
    img:nth-child(7){
        transform: translate(0px,0px) rotate(0deg);
    }
    img:nth-child(8){
        transform: translate(10px,100px) rotate(20deg);
    }
    img:nth-child(9){
        transform: translate(100px,60px) rotate(180deg);
    }
    .shield:hover img{
        transform: translate(0,0) rotate(0);
    }
</style>
</head>
<body>
	<div class="shield">
	<img src="images/shield_1_01.png" alt="">
	<img src="images/shield_1_02.png" alt="">
	<img src="images/shield_1_03.png" alt="">
	<img src="images/shield_1_04.png" alt="">
	<img src="images/shield_1_05.png" alt="">
	<img src="images/shield_1_06.png" alt="">
	<img src="images/shield_1_07.png" alt="">
	<img src="images/shield_1_08.png" alt="">
	<img src="images/shield_1_09.png" alt="">
    </div>
</body>
</html>
