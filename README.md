<!DOCTYPE html>
<html>
<head>
  <title>Login Page</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial;
      background-color:lightgrey;
    }
    .container {
      max-width: 400px;
      margin: 40px auto;
      padding: 20px;
      background-color: #fff;
      border: 1px solid;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .l {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }
    h2 {
      margin-bottom: 20px;
      text-align: center;
    }
    label {
      display: block;
      margin-bottom: 10px;
    }
    input {
      width: 100%;
      height: 40px;
      margin-bottom: 20px;
      padding: 10px;
      border: 1px solid #ccc;
    }
    button {
      width: 100%;
      height: 40px;
      background-color: #4CAF50;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #3e8e41;
    }
    p {
      margin-top: 20px;
    }
    a {
      text-decoration: none;
      color: #4CAF50;
    }
    a:hover {
      color: #3e8e41;
    }
    select {
      width: 100%;
      height: 40px;
      margin-bottom: 20px;
      padding: 10px;
      border: 1px solid #ccc;
    }
    input[type="radio"] {
      width: 20px;
      height: 20px;
      margin: 10px;
      accent-color: #4CAF50;
    }
    input[type="checkbox"] {
      accent-color: #4CAF50;
      width: 20px;
      height: 20px;
      margin: 10px;
    }
    input[type="checkbox"]:checked {
      background-color: #34C759; 
      border: 1px solid #34C759;
    }
    .radio-group {
      display: flex;
      flex-direction: row;
      align-items: center;
      margin-bottom: 20px;
    }
    .radio-group label {
      margin-right: 20px;
    }
    .radio-group input[type="radio"] {
      background-color: #4CAF50;
    }
    .checkbox-group {
      display: flex;
      flex-direction: row;
      align-items: center;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="login">
      <h2>Login</h2>
      <form>
        <label for="l">Username:</label>
        <input type="text" id="l" name="l"  placeholder="Enter your email" required>

        <label for="p">Password:</label>
        <input type="password" id="p" name="p" placeholder="Enter the password" required>

        <label for="country">Country:</label>
        <select id="country" name="country">
          <option value="">Select a country</option>
          <option value="india">INDIA</option>
          <option value="usa">USA</option>
          <option value="uk">UK</option>
        </select>

        <div class="radio-group">
          <input type="radio" id="male" name="gender" value="male">
          <label for="male">Male</label>
          <input type="radio" id="female" name="gender" value="female">
          <label for="female">Female</label>
        </div>

        <div class="checkbox-group">
          <input type="checkbox" id="robot" name="robot">
          <label for="robot">I'm not a robot</label>
        </div>

        <button>Login</button>
        <p>Don't you have an account?<a href="file:///C:/Users/mahi/OneDrive/Documents/css-assignment-17.html"> Sign up</a> </p>
      </form>
    </div>
  </div>
</body>
</html>
