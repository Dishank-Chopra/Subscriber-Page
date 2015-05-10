<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">

       <script language = "Javascript">
        function checkEmail(emailId) {
        if (/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/.test(emailId)){
        document.write("You have entered valid email.");
        return true;
        }    
        return false;
        }

        function ValidateEmail(){
            var emailID=document.form.email;

            if ((emailID.value == null)||(emailID.value == "")){
                alert("Please Enter your Email ID")
                emailID.focus()
                return false
            }

            if (checkEmail(emailID.value)==false){
                emailID.value=""
                alert("Invalid Email Adderess");
                emailID.focus()
                return false
            }
                alert('valid');
                return true
         }
        </script>

        <title>Email Registration</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <style>
        .box{display:block; float:left; width:20px; margin:0 45px 0 0; padding:0;}
        .textbox {
            display:block;
            width:340px;
			font-size: 24px;
			color: black;
			font-family: Arial, Helvetica, sans-serif;
			border-style: none;
			border-width: medium;
			height:35px; 
			padding:5px 10px 5px 10px;
        }
	
		
	</style>
        
       
    </head>
   
    <body> 
        
        <form name="form" method="post" onSubmit="return ValidateEmail()" action="jspdatabase.jsp">    
      
         <div class="box" style="position: absolute; top: 50px; height: 50px; width: 100px; left: 100px">
            <label id="label" for="name" style="font-weight: bold">Email</label>
            <input id="Text" type="text" name="email" value="" class="textbox"/>
         </div>
        
        <input id="Button" type="submit" value="Submit" style="position: absolute; height: 35px; width: 100px; top: 68px; left: 470px; border: 0px; background-color: #555555; color: #FFFFFF; font-family: Arial, Helvetica, sans-serif; font-size: x-large;" />
        
        
       
            
        </body>
</html>
