<!DOCTYPE html>   
<html>   
<head>		<!-- Document Header Starts -->
<link rel="stylesheet" href="styles.css">		<!-- Defining the Stylesheet --> 	
</head>		<!-- Document Header Ends -->
<title></title>  
<style>   
	Body		 	
		{  
			font-family: Calibri, Helvetica, sans-serif;  
			margin: 0px 500px;
			width: 25%;
		}  
	
	button		
		{      
			width: 110%;  
			color: white;   
			padding: 0px;   
			margin: 10px 0;   
			border: 0px solid;  
			cursor: pointer;
			border-radius: 25px;
		} 
	
	form		 
		{   
			border: 70px solid #FFFFFF;
			border-radius: 25px;
			width: 65%;
			margin: 52px 0;
		}   
	
	input[type=text],input[type=password]		
		{   
			width: 110%;   
			margin: 10px 0;  
			padding: 12.5px 40px;      
			border-radius: 25px;
			box-sizing: border-box; 
			border: 0px solid;
		}  
	
	button:hover		 
		{   
			opacity: 0.7;   
		}    
	
	.container		
		{   
			padding: 1px;
			height : 450px;		
			box-sizing: border-box;
			background-color: white;
		}
	   
	#username		
		{
			background-image: url(https://icon-library.com/images/username-icon/username-icon-14.jpg);
			background-size: 35px;   
			background-repeat: no-repeat;
		}   
    
	#password		
		{
			background-image: url(https://w7.pngwing.com/pngs/529/248/png-transparent-padlock-lock-ico-icon-unlocked-lock-s-apple-icon-image-format-unlocked-lock-cliparts-security-thumbnail.png);  
			background-repeat: no-repeat;
			background-size: 28px;
			position:left;
		}
	
	#button		
		{
			background-image: url(https://media.istockphoto.com/photos/pink-yellow-and-orange-colors-defocused-abstract-smooth-background-picture-id1256009727?k=20&m=1256009727&s=170667a&w=0&h=qOkYEBxNGhH8O8aNHNEYV0NBmehCxr3vXyRMTbqoB9I=);
			background-size: 300px;
			width: 110%;   
			margin: 10px 0;  
			height: 47px ;
			font-size:20px;
			background-repeat: no-repeat;
		} 
		
</style>    
<body text="#4a4848" style="background-image: url(https://mcdn.wallpapersafari.com/medium/1/29/3I8Lah.jpg);background-size: 100% 100%;background-repeat: no-repeat;">		<!-- Defining the image source to background of the webpage -->   
    <form>		<!-- Form Declaration Starts Here --> 
	
        <div class="container"> 	<!-- Calling the Class "container" --> 
		
			<center>		<!-- Center Align of the Text Starts here -->
		
			<h1>Login</h1>		<!-- Printing the Text --> 
         
            <input type="text" placeholder="Username" name="username" class="username" id="username" required style="background-color:#f0f0f0;"><br>		<!-- "Username" Textbox Input Tag Declaration -->     
            <input type="password" placeholder="Password"name="password" class="password" id="password"  required style="background-color:#f0f0f0;">		<!-- "Password" Textbox Input Tag Declaration -->
			
			</center>		<!-- Center Align of the Text Ends here --> 
                   
            <input type="checkbox" checked="checked" style="text-indent: 80px;background:#ffc273;">		<!-- "Remember me" Checkbox Input Tag Declaration -->
            <font color="grey">Remember me</font><br>		<!-- Printing the Text -->
			     
            <p><button type="button" class="button" id="button">LOG IN</button><br></p>		<!-- "Log In" Button Input Tag Declaration -->
			
			<center>		<!-- Center Align of the Text Starts here -->		
			
            <font color="grey" style="margin-left: 13px;" >Forget Password</font>		<!-- Printing the Text -->
            
            <br><br><br><br><br><br><br>		<!-- Breaking the Line -->
 
            <font color="grey">Not a member? </font><font color="#228ee6">Sign up now</font>		<!-- Printing the Text -->
			
			</center>		<!-- Center Align of the Text Ends here -->
            
        </div>		<!-- Termination of the tag -->
		
    </form>		<!-- Form Declaration Ends here -->     
</body>     
</html> 


