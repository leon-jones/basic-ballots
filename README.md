# basic-ballots
Captone project
<!DOCTYPE HTML>
<html>
<body>
    <head>
        <title> SNHU-A-Palooza: the Concert, Registration page</title>
    
    <link rel="stylesheet" href="/css/main.css" type="text/css">
        <style>
            .center {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
}
        </style>
        
        <script>
function validateForm() {
    var a = document.forms["myForm"]["FirstName"].value;
    if (a == "") {
        alert("First Name must be filled out, Everyone has a First Name");
        return false;
    }
    
    var b = document.forms["myForm"]["LastName"].value;
    if (b == "") {
        alert("Your not Sting, Bono, Cher or Rhiana so a last name must be filled out");
        return false;
    }
    var c = document.forms["myForm"]["Email"].value;
    if (c == "") {
        alert("Valid email address must be filled out");
        return false;
    }
}
</script>

    </head>
    

   <img src="/images/Pic05Mid.jpg" 
     alt="Registration banner here" class="center" 
     style="width:50%"> 
    <br>    
    <p>INFORMATION ABOUT THE CONCERT AND REGISTRATION PROCESS.
     POSSIBLY IN A BOX OF SOME SORT</p>  
    <br>
    
        <title> My first form!</title>
    
<form name="myForm" action="registration.php" onsubmit="return validateForm()" method="post">

 First Name: <input type="text" name="FirstName">
<span class="error">* <?php echo $fnameErr;?></span>
<br><br>

Last Name: <input type="text" name="LastName">
<span class="error">* <?php echo $lnameErr;?></span>
<br><br>

Email Address: <input type="text" name="Email">
<span class="error">* <?php echo $emailErr;?></span>
<br><br>
    <input type="submit" value="Submit">
</form>

	
    
    
    
    
    
    
    
    <img src="/images/Pic01Main.jpg" 
         alt="SNHU logo" class="center" 
     style="width:1000px;height:300px;">
    
    
    
    </body>
    </html>
