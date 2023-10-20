<!DOCTYPE html>
<html>
<head>
  <title>You are Welcome</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    .login-form {
      padding: 20px;
      background-color: #f8f8f8;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .login-form label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }

    .login-form input[type="text"],
    .login-form input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 3px; 
      border: 1px solid #ff7e7e;
      background-color: #ff7e7e;
    }

    .login-form input[type="submit"] {
      display: block;
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 3px;
      background-color: #000802;
      border: #67f045;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }
    

    .login-form input[type="submit"]:hover {
      background-color: #67f045;
    }
  </style>
</head>
<body>
  <div class="login-form">
    <h2>You are Welcome!</h2>
    <h6> please enter your login and password to enter a privat account</h6>
    <form>
      <label for="username">Email:</label>
      <input type="text" id="username" name="username" required>
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
      <input type="submit" value="Login">
      <label for="forgot password?" align="center"><u><a href="https://github.com/">forgot password?</a></u></label>
      <h5 align="center"> Don't have an account?</h5>
      <input type="submit" value="create an account">
    </form>
  </div>
</body>
</html>
