# registration-form


<!DOCTYPE html>
<html>
<head>
<title>
Basic I
</title>
</head>
<body>
    <h1>
    My Registration Form
    </h1>
    </body>
    <form action="process.php" method="post">
    <p>Please Register</p>
    <label for="first_name">First Name:</label>
    <input type="text" id="first_name" name="first_name">
   
    <label for="last_name">Last Name:</label>
    <input type="text" id="last_name" name="last_name">
   
    <label for="email">Email:</label>
    <input type="text" id="email" name="email">
   
    <p>Select your gender:</p>
    <label for="male">Male</label>
    <input type="radio" id="male" name="gender" value="male">
   
    <label for="female">Female</label>
    <input type="radio" id="female" name="gender" value="female">
    
    <label for="decline">Prefer not to say</label>
    <input type="radio" id="decline" name="gender" value="decline">
   
    <p>Select 3 of your favorite colors:</p>
    <label for="blue">Blue</label>
    <input type="checkbox" id="blue" name="color" value="blue">
    
    <label for="green">Green</label>
    <input type="checkbox" id="green" name="color" value="green">
   
    <label for="red">Red</label>
    <input type="checkbox" id="red" name="color" value="red">
    
    <label for="black">Black</label>
    <input type="checkbox" id="black" name="color" value="black">
   
    <label for="purple">Purple</label>
    <input type="checkbox" id="purple" name="color" value="Purple">
    
    <p>Say a few words about yourself:</p>
    <textarea name="description"></textarea>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password">
   <label for="pw_confirm">Password Confirmation:</label>
   <input type="password" id="pw_confirm" name="password_confirmation">
   
   <input type="submit" value="Click here to register">
</form>
</html>
