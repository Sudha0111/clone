# clone google
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Google Search</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
  <style>
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      background-color: #f8f8f8;
    }

    .search-container {
      max-width: 600px;
      margin-bottom: 40px;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 10px;
      background-color: #fff;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .search-input {
      border: 1px solid #ddd;
      border-radius: 25px;
      padding: 10px 20px;
      font-size: 18px;
      width: 100%;
    }

    .search-btn {
      border: 1px solid #007bff;
      border-radius: 25px;
      padding: 10px 30px;
      font-size: 18px;
      background-color: #007bff;
      color: #fff;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .search-btn:hover {
      background-color: #0056b3;
    }

    .logo-container {
      margin-top: 40px;
    }

    .logo {
      font-size: 80px;
      font-weight: bold;
      font-family: 'Arial', sans-serif;
      color: #4285F4;
    }

    .o1 { color: #EA4335; }
    .o2 { color: #FBBC05; }
    .o3 { color: #34A853; }
    .o4 { color: #4285F4; }

    .o1, .o2, .o3, .o4 {
      display: inline-block;
      transform-origin: center;
      animation: bounce 2s infinite alternate;
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
  </style>
</head>
<body>

<!-- Google Logo -->
<div class="logo-container">
  <div class="logo">
    <span class="o1">G</span>
    <span class="o2">o</span>
    <span class="o3">o</span>
    <span class="o4">g</span>
    <span class="o1">l</span>
    <span class="o2">e</span>
  </div>
</div>

<!-- Google Search Bar -->
<div class="container search-container">
  <div class="row justify-content-center">
    <div class="col-md-8">
      <form action="https://www.google.com/search" method="GET">
        <div class="input-group">
          <input type="text" class="form-control search-input" name="q" placeholder="Search Google...">
          <button type="submit" class="btn btn-primary search-btn">Search</button>
        </div>
      </form>
    </div>
  </div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>
