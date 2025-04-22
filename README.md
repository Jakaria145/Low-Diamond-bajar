<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Low Diamond Bazar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #333;
    }
    .package {
      background-color: #fff;
      margin: 10px auto;
      padding: 10px;
      border-radius: 10px;
      width: 300px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .btn {
      background-color: #4CAF50;
      color: white;
      padding: 5px 15px;
      font-size: 14px;
      margin-top: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .btn:hover {
      background-color: #45a049;
    }
    .form-section {
      background-color: #fff;
      margin: 30px auto;
      padding: 20px;
      border-radius: 10px;
      width: 320px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    input {
      width: 90%;
      padding: 8px;
      margin: 8px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .submit-btn {
      background-color: #FF6347;
      color: white;
      padding: 10px 20px;
      font-size: 16px;
      margin-top: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .submit-btn:hover {
      background-color: #e6533d;
    }
  </style>
</head>
<body>
  <h1>💎 Low Diamond Bazar 💎</h1>

  <div class="package">১০০ Diamond - ৭৫ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">২৭০ Diamond - ২০০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">৫৩০ Diamond - ৪৫০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">১০০০ Diamond - ৮৮০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">২৫০০ Diamond - ১৫০০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">Weekly - ১৪০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">2x Weekly - ২৬০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">4x Weekly - ৫৫০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">Monthly - ৭৪০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">2x Monthly - ১৪৬০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>
  <div class="package">Level up Pass - ১৪০ টাকা<br><button class="btn" onclick="scrollToForm()">Buy</button></div>

  <div id="orderForm" class="form-section">
    <h2>অর্ডার করুন</h2>
    <form action="https://formspree.io/f/your-form-id" method="POST">
      <input type="text" name="player_id" placeholder="🔹 Player ID" required><br>
      <input type="text" name="transaction_id" placeholder="🔹 Transaction ID" required><br>
      <button class="submit-btn" type="submit">✅ Submit Order</button>
    </form>
  </div>

  <script>
    function scrollToForm() {
      document.getElementById('orderForm').scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</body>
</html>
