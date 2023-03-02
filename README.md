# reg
empregistrationform
<!DOCTYPE html>
<html>
<head>
<h1> Company Registration Form</h1>
</head>
<body bgcolor="Lightpink"> 
<br> <br>
<form>
<label> Firstname </label> 
<input type="text" name="firstname" /> <br> <br> 
<label> Middlename: </label> 
<input type="text" name="middlename"/> <br> <br> 
<label> Lastname: </label> 
<input type="text" name="lastname" /> <br> <br> 

<label> Gender : </label><br> 
<input type="radio" name="male"/> Male <br> 
<input type="radio" name="female"/> Female <br> 
<input type="radio" name="other"/> Other <br> <br> 
<label> Mobile No : </label> 
<!---- <input type="text" name="country code" value="+91" size="2"/> --> 
<input type="text" name="phone" size="10"/> <br> <br> 
<!--Address 
<br> 
<textarea cols="80" rows="5" value="address"> 
</textarea> 
<br> <br> -->

Email: 
<input type="email" id="email" name="email"/> <br> 
<br> <br> 
Password: 
<input type="Password" id="pass" name="pass"> <br> 
<br> <br> 
<!-- Re-type password: 
<input type="Password" id="repass" name="repass"> <br> <br> 
<input type="button" value="Submit"/> -->
<label for="Qualification">Choose Your Qualification:</label>
<select name="Qualification Name" id="Qualification Name">
<option value="IT">IT</option>
<option value="COMPUTER">COMPUTER</option>
<option value="Mechanical">Mechanical</option>
<option value="Electrical">Electrical</option>
</select> <br> <br> 

<label> Current Status: </label><br> 
<input type="radio" name="Student"/> Student <br> 
<input type="radio" name="Employed Graduate"/> Employed Graduate <br> 
<input type="radio" name="Unemployed Graduate"/> Unemplyed Graduate <br> <br> 
<input type="submit">
<input type="reset">
</form> 
</body> 
</html> 

