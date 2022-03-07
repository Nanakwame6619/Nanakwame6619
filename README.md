<html>
<head>
<title> LogIn Page </title>
</head>
<body bgcolor="Brown">
    <p align="center">
    <img src="me.jpeg" alt="me"  width="300" height="350">
        Hey there. It's Patrick Asiedu here. I'm tall and dark in complexion. 
        <br>
        I study at the University Of Ghana, Legon.
        <br>
        I read B.s.c.Information Technology.I'm in Commonwealth hall .<br>
        I hope to graduate in 2024.
        </p>
        <table border ="2" align="left">
            <tr>
            <th>Name Of School</th>
            <th>Course Of Study</th>
            <th>Start and End Date</th>
            </tr>
            <tr>
                <td>University Of Ghana</td>
                <td>Bsc. Information  Technology</td>
                <td>2020 - 2024  </td>
            </tr>
            <tr>
                <td>Oyoko Methodist Senior high sch </td>
                <td>General Arts</td>
                <td>2016- 2019</td>
                </tr>
                <tr>
                    <td>Solomon school  J.H.S</td>
                    <td>All G.E.S Certified subjects for B.E.C.E</td>
                    <td>2013- 2016  </td>
                     </tr>
                    </table>
                    <br><br><br>
    <fieldset style="width:300px" bgcolor="blue" >
        <legend  >Login </legend>
   <p align="left">Username :
        <input type="text" placeholder "Enter UserName"name = 'UserName' required>
   </label> </p>
    <p align="left"><label>Password :&nbsp;
        <input type="Password" placeholder "Enter Password"name = 'Password' required>
    </label> </p>
    <p align="left"><label>Telephone :
    <input type="tel" placeholder "Enter Telephone Number"name = 'Telephone Number' required>
</label> </p>
<p >Gender    :
  <input type="radio" id="male" name="Gender" value="Male">Male
  <input type="radio" id="female" name="Gender" value="Female">Female
  <input type="radio" id="other" name="Gender" value="Custom">Custom
  </p>
  <p ><label for="idt">ID Type :</label>
    <select name="idt"   width="174" style="width: 174px">
      <option value="Ghana Card">Ghana Card</option>
       <option value="Voter's ID">Voter's Id</option>
       <option value="Passport">Passport</option>
   <option value="Driver's license">Driver's license</option>
   <option value="NHIS">NHIS</option>
   </select>
   </p>
   <p > 
       <label  width="174%">ID N0 :
    <input type="text" placeholder "Enter ID N0"name = 'ID N0' required>
</label> </p>
    <button type="Submit" bgcolor="blue">Login</button>
    <button type="button " class="cancelbtn "> Cancel </button>
    <input type="checkbox" checked= "checked"> 
</table>
</fieldset>
</body>
</html>
