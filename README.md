html
Copy
Edit
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Finance Portal - Login</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="login-container">
    <h2>Finance Company Login</h2>
    <form id="loginForm">
      <input type="text" id="username" placeholder="Username" required />
      <input type="password" id="password" placeholder="Password" required />
      <button type="submit">Login</button>
      <p id="error" style="color: red;"></p>
    </form>
  </div>

  <script src="script.js"></script>
</body>
</html>
