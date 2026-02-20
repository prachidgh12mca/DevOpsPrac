<!DOCTYPE html>
<html>
<head>
    <title>Simple Contact Form</title>
</head>
<body>

    <h2>Contact Form</h2>

    <form action="#" method="post">
        
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password"><br><br>
        
        <label for="gender">Gender:</label><br>
        <input type="radio" name="gender" value="male"> Male
        <input type="radio" name="gender" value="female"> Female<br><br>
        
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="30"></textarea><br><br>
        
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
        
    </form>

</body>
</html>
