<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sign Up Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      min-height: 100vh;
      background-color: #f5f5f5;
    }
    
    .container {
      display: flex;
      width: 100%;
      max-width: 1200px;
      margin: auto;
      background: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    
    .image-section {
      flex: 1;
      background: url('https://via.placeholder.com/600x800') center/cover no-repeat;
      min-height: 600px;
    }
    
    .form-section {
      flex: 1;
      padding: 40px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    
    h2 {
      font-size: 24px;
      margin-bottom: 30px;
      color: #333;
    }
    
    label {
      display: block;
      margin-bottom: 8px;
      font-weight: 500;
    }
    
    input {
      width: 100%;
      padding: 12px;
      margin-bottom: 20px;
      border: 1px solid #ddd;
      border-radius: 4px;
      box-sizing: border-box;
    }
    
    .terms {
      display: flex;
      align-items: center;
      margin: 20px 0;
    }
    
    .terms input {
      width: auto;
      margin: 0 10px 0 0;
    }
    
    .actions {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    
    .btn-signup {
      background: #4285f4;
      color: white;
      border: none;
      padding: 12px 30px;
      border-radius: 4px;
      cursor: pointer;
      font-weight: bold;
    }
    
    .signin-link {
      color: #4285f4;
      text-decoration: none;
    }
    
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
      .image-section {
        min-height: 300px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="image-section">
      <!-- Image will be displayed here -->
      <!-- Replace with your actual image path -->
    </div>
    
    <div class="form-section">
      <h2>Sign Up</h2>
      
      <label>Full Name</label>
      <input type="text" value="Zachary Davis">
      
      <label>Email</label>
      <input type="email" value="zachary-davis@example.com">
      
      <label>Username</label>
      <input type="text" value="zacharydavis">
      
      <label>Password</label>
      <input type="password" value="***********">
      
      <label>Repeat Password</label>
      <input type="password" value="***********">
      
      <div class="terms">
        <input type="checkbox" id="terms" checked>
        <label for="terms">I agree to the Terms of User</label>
      </div>
      
      <div class="actions">
        <button class="btn-signup">Sign Up</button>
        <a href="#" class="signin-link">Sign in →</a>
      </div>
    </div>
  </div>
</body>
</html>