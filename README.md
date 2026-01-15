# goodboy
this  is my first project
<br>
writer- Shiva kumar yadav 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sample HTML Form</title>
</head>
<body>
  <h2>Registration Form</h2>
  <form action="/submit" method="post">
    
    <!-- Text input -->
    <label for="name">Full Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>
    
    <!-- Email input -->
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>
    
    <!-- Password input -->
    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required><br><br>
    
    <!-- Radio buttons -->
    <p>Gender:</p>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label><br>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label><br><br>
    
    <!-- Dropdown -->
    <label for="country">Country:</label><br>
    <select id="country" name="country">
      <option value="india">India</option>
      <option value="usa">USA</option>
      <option value="uk">UK</option>
    </select><br><br>
    
    <!-- Checkbox -->
    <input type="checkbox" id="subscribe" name="subscribe" value="newsletter">
    <label for="subscribe">Subscribe to newsletter</label><br><br>
    
    <!-- Submit button -->
    <input type="submit" value="Register">
    
  </form>
</body>
</html>

