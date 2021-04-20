<!DOCTYPE html>
<html lang="en">
<head>
		<title>Form</title>
	<link rel="stylesheet" href="index.css">
	
	<style>
					
					
			.form_holder{
	background-color: white;
	border-radius: 25px;
	box-shadow: 1px 2px 2px grey, -1px -4px 4px grey;
	height: 10%;
	width: 80%;
	margin-top: 15%;
	padding: 5px;
	
}
body{
		font-family: sans-serif;
		font-size: 18px;
}
form{
 margin: center;
 padding: center;
}
input{
	padding: 14px;
	margin: 7px;
	border-radius: 16px;
	box-shadow: 2px 3px 2px grey, -2px -3px 4px grey;
	width: 70%;
	font-weight: bold;
}
input[type="submit"]{
			color: red;
			background-color: white;
			font-weight: bolder;
			width: 30%;
}
input[type="submit"]:hover{
				color: blue;
				background-color: white;
}
		
					
					
	</style>
	
</head>
<body>
<center>
<div class="form_holder">
				
<p style="font-size: 24px;"><b>Login Here</b></p>	<br>
<form>
<input type="text" placeholder="enter Name" required=""><br>
<input type="text" placeholder="username" required=""><br>
<input type="number" placeholder="mobile number" required=""><br>
<input type="email" placeholder="enter email address" required=""><br>
<input type="password" id="password" placeholder="enter password" required=""><br>


<input type="password" id="cpassword" placeholder="confirm password" required=""><br>
<input type="submit" value="Login">
			</form>	
</div>		
Don't have an account?<br>
<a href="www.jamextechsolution.wordpress.com">Register Here</a>
	</center>		
</body>
</html>
