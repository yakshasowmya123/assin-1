<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login Form</title>
  <!-- Bootstrap 5 CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light d-flex justify-content-center align-items-center vh-100">

  <div class="card p-4 shadow" style="width: 100%; max-width: 400px;">
    <h3 class="text-center mb-4">Login Form</h3>
    <div class="mb-3">
      <input type="number" class="form-control" id="num" placeholder="Enter Number"/>
    </div>
    <div class="mb-3">
      <input type="password" class="form-control" id="pass" placeholder="Enter Password" />
    </div>
    <button class="btn btn-primary w-100" onclick="login()">Login</button>

    <p id="res"></p>
  </div>

  <script src="index.js"></script>
  <!-- Bootstrap JS Bundle (Optional if needed for components like modals) -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

