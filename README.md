# ITEL_203
<!DOCTYPE html>  
<html>  
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<style>  
body{  
  font-family: Courier, Verdana, sans-serif;  
  background-color: #5CB3FF;  
}  
.container {  
    padding: 50px;  
  background-color: #5CB3FF;  
}  
  
input[type=text], input[type=password], textarea {  
  width: 100%;  
  padding: 15px;  
  margin: 5px 0 22px 0;  
  display: inline-block;  
  border: none;  
  background: #F0FFFF;  
}  
input[type=text]:focus, input[type=password]:focus {  
  background-color: orange;  
  outline: none;  
}  
 div {  
            padding: 10px 0;  
         }  
hr {  
  border: 1px solid #f1f1f1;  
  margin-bottom: 25px;  
}  
.registerbtn {  
  background-color: #151B54;  
  color: white;  
  padding: 16px 20px;  
  margin: 8px 0;  
  border: none;  
  cursor: pointer;  
  width: 100%;  
  opacity: 0.9;  
}  
.registerbtn:hover {  
  opacity: 1;  
}  
</style>  
</head>  
<body>  
<form>  
  <div class="container">  
  <center>  <h1> Student Registeration Form</h1> </center>  
  <hr>  
  <label> First name </label>   
<input type="text" name="firstname" placeholder= "First name" size="15" required />   
<label> Middle name: </label>   
<input type="text" name="middlename" placeholder="Middle name" size="15" required />   
<label> Last name: </label>    
<input type="text" name="lastname" placeholder="Last name" size="15" required />   
<div>  
<label>   
Course :  
</label>   
  
<select>  
<option value="Course">Course</option>  
<option value="BSIT">BSIT</option>  
<option value="BSIS">BSIS</option>  
<option value="BSCS">BSCS</option> 
</select>  
</div>  
<div>  
<label>   
Gender :  
</label><br>  
<input type="radio" value="Male" name="gender" checked > Male   
<input type="radio" value="Female" name="gender"> Female   
<input type="radio" value="Other" name="gender"> Other  
  
</div>  
<label>   
Phone :  
</label>  
<input type="text" name="country code" placeholder="Country Code"  value="+63" size="2"/>   
<input type="text" name="phone" placeholder="Phone no." size="10"/ required>   
Current Address :  
<textarea cols="80" rows="5" placeholder="Current Address" value="address" required>  
</textarea>  
 <label for="email"><b>Email</b></label>  
 <input type="text" placeholder="Enter Email" name="email" required>  
  
    <label for="psw"><b>Password</b></label>  
    <input type="password" placeholder="Enter Password" name="psw" required>  
    
  <a href = ""> Forgot password? click here</a>
  
    <button type="submit"
     class="registerbtn">Register</button>    
</form>  
</body>  
</html>
