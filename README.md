<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Welcome to My Simple Website</title>
<style>
  :root {
    --primary-color: #4a90e2;
    --secondary-color: #50e3c2;
    --bg-color: #f4f7fa;
    --text-color: #333;
    --button-color: #4a90e2;
    --button-hover: #357abd;
  }
  body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: var(--bg-color);
    color: var(--text-color);
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2rem;
    min-height: 100vh;
  }
  header {
    text-align: center;
    margin-bottom: 1rem;
  }
  header h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    color: var(--primary-color);
  }
  header p {
    font-size: 1.2rem;
    margin: 0 auto;
    max-width: 600px;
  }
  button.contact-btn {
    margin-top: 2rem;
    background-color: var(--button-color);
    color: white;
    border: none;
    padding: 0.75rem 1.5rem;
    border-radius: 6px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
    box-shadow: 0 4px 6px rgba(74,144,226,0.4);
  }
  button.contact-btn:hover {
    background-color: var(--button-hover);
  }
  @media (max-width: 480px) {
    header h1 {
      font-size: 2rem;
    }
    header p {
      font-size: 1rem;
      padding: 0 1rem;
    }
  }
</style>
</head>
<body>
  <header>
    <h1>Welcome to My Simple Website</h1>
    <p>This is a clean and modern web page you can host for free on the internet. Click the button below to say hello!</p>
    <button class="contact-btn" onclick="sayHello()">Contact Me</button>
  </header>
  <script>
    function sayHello() {
      alert('Hello! Thanks for visiting CA Shafaf website.');
    }
  </script>
</body>
</html>
