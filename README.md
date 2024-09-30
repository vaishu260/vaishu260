<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Information Form</title>
</head>
<body>
    <h1>Personal Information Form</h1>
    <form action="#" method="post">
        <label for="name">First Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="name">Last Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label>Gender:</label>
        <div>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
        
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
       
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
        </div><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob"><br><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone"><br><br>

        <label for="address">Address:</label>
        <textarea id="address" name="address"></textarea><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required><br><br>

        <label for="confirm-password">Confirm Password:</label>
        <input type="password" id="confirm-password" name="confirm-password" required><br><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
