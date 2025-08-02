<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Account Owner Login</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f4f4f4; display: flex; justify-content: center; align-items: center; height: 100vh; }
    form { background: white; padding: 20px; border-radius: 10px; width: 300px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
    input { width: 100%; padding: 10px; margin: 8px 0; border: 1px solid #ccc; border-radius: 5px; }
    button { width: 100%; padding: 10px; background: #007bff; color: white; border: none; border-radius: 5px; cursor: pointer; }
    button:hover { background: #0056b3; }
    .message { margin-top: 10px; font-size: 14px; color: green; }
    .error { color: red; }
    a { display: block; margin-top: 10px; text-align: center; font-size: 14px; color: #007bff; text-decoration: none; }
    a:hover { text-decoration: underline; }
  </style>
</head>
<body>
  <form id="loginForm">
    <h3>Account Owner Login</h3>
    <input type="email" id="email" placeholder="Email Address" required />
    <input type="password" id="password" placeholder="Password" required />
    <button type="submit">Login</button>
    <p class="message" id="successMsg"></p>
    <p class="message error" id="errorMsg"></p>
    <a href="register.html">Don't have an account? Register here</a>
  </form>

  <script type="module">
    import { createClient } from 'https://cdn.jsdelivr.net/npm/@supabase/supabase-js/+esm';

    // Replace with your Supabase credentials
    const supabaseUrl = 'https://YOUR-PROJECT-ID.supabase.co';
    const supabaseKey = 'YOUR-ANON-PUBLIC-KEY';
    const supabase = createClient(supabaseUrl, supabaseKey);

    const form = document.getElementById('loginForm');
    const successMsg = document.getElementById('successMsg');
    const errorMsg = document.getElementById('errorMsg');

    form.addEventListener('submit', async (e) => {
      e.preventDefault();

      const email = document.getElementById('email').value;
      const password = document.getElementById('password').value;

      const { data, error } = await supabase.auth.signInWithPassword({
        email,
        password
      });

      if (error) {
        errorMsg.textContent = error.message;
        successMsg.textContent = '';
      } else {
        successMsg.textContent = "Login successful! Redirecting...";
        errorMsg.textContent = '';
        // Redirect to dashboard (change to your dashboard URL)
        setTimeout(() => {
          window.location.href = "dashboard.html"; 
        }, 1000);
      }
    });
  </script>
</body>
</html>
