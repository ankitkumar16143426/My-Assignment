# My-Assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
        <form>     
        <fieldset>
            <legend><b>Personal Details </b></legend> <br> 
            <b> <label> FirstName </label>  </b>       
        <input type="text" name="firstname" size="15"/> <br> <br>  
        <b> <label> MiddleName: </label> </b>     
        <input type="text" name="middlename" size="15"/> <br> <br>  
        <b> <label> LastName: </label> </b>        
        <input type="text" name="lastname" size="15"/> <br> <br>  
        <label>   
       <b> Course :  </b>  
        </label>   
        <select>  
        <option value="Course">Course</option>  
        <option value="BCA">BCA</option>  
        <option value="BBA">BBA</option> 
        <option value="B.com">B.com</option> 
        <option value="B.Tech">B.Tech</option>  
        <option value="MBA">MBA</option>  
        <option value="MCA">MCA</option>  
        <option value="M.Tech">M.Tech</option>
        <option value="M.Phil">M.Phil</option>
        <option value="PhD">PhD</option>  
        </select>  
        <br>  
        <br>  
        <label>   
        <b>Gender :</b>  
        </label for="gender" ><br>  
        <input type="radio" name="gender"/> Male <br>  
        <input type="radio" name="gender"/> Female <br>  
        <input type="radio" name="gender"/> Other  
        <br>  
        <br>  
         <b> <label >DOB</label></b>
          <input type="datetime-local" name="" id="">
          <br> <br>
        <label>   
       <b> Phone : </b> 
        </label>  
        <input type="text" name="country code"  value="+91" size="2" disabled/>   
        <input type="tel" name="phone" maxlength="10"  size="10"/> <br> <br>  
        <b><label for="">Address </label></b>
        <br>  
        <textarea cols="80" rows="5" value="address">  
        </textarea>  
        <br> <br>  
        <b> <label>Email:</label> </b>
        <input type="email" id="email" name="email"/> <br>    
        <br>  
       <b> <label for="">Password:</label> </b>
        <input type="Password" id="pass" name="pass"> <br>   
        <br>  
        <b> <label for="">Re-type password:</label> </b>
        <input type="Password" id="repass" name="repass"> <br> <br>
        <input type="checkbox" name="" id="">Agree to terms and conditions
        <br><br>
        <b> <label for="">Choose File</label> </b>
        <input type="file" name="" id="">
        <br><br>
        <b> <label for="">Choose Color</label> </b>
        <input type="color" name="" id="">
        <br><br>
        <input type="reset" value="Reset"/> 
        <input type="button" value="Submit"/>  
        </fieldset>
        </form>  
</body>
</html>
