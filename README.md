<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>title</title>
</head>
<body>
<form method="get" action="simpleform.html">
<h2>Order Form</h2>
    <p>what would you like to buy?</p>
    <select>
      <option value = " ">A</option>
      <option>B (+ 0.5$)</option>
      <option>C (+ 0.5$)</option>
    </select>
  <p>How many would you like to order?</p>
  <input type="radio" name="rd"/> 1 - $10 <br/>
  <input type="radio" name="rd"/> 2 - $20 <br/>
  <input type="radio" name="rd"/> 3 - $25 <br/>
  >
  <p>Name <span style="color: red">*</span> </p>
  <input type = "text" name="firstname" placeholder="FirstName" size="15"/>
  <input type = "text" name="lastname" placeholder="LastName" size="15"/>
  <p>Email</p>
  <input type = "text" name="email" size="35"/>
  <p>Phone Number</p>
  <input type = "text" name="phone1" size="5"/> -
  <input type = "text" name="phone2" size="5"/> -
  <input type = "text" name="phone3" size="5"/>
  <p><input type = "button" name="btSubmit" value="Submit"/></p>
</form>
</body>
</html>
