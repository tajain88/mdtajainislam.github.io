# mdtajainislam.github.io<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>গরুর ওষুধের দোকান</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f8f8f8;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #2e7d32;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #388e3c;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #2e7d32;
    }
    .container {
      padding: 20px;
    }
    .product {
      background-color: white;
      border: 1px solid #ddd;
      margin-bottom: 20px;
      padding: 15px;
      border-radius: 5px;
    }
    .product h3 {
      margin-top: 0;
    }
    footer {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 5px;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #388e3c;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    form button:hover {
      background-color: #2e7d32;
    }
  </style>
</head>
<body>

<header>
  <h1>গরুর ওষুধের দোকান</h1>
  <p>বিশ্বস্ত পশু চিকিৎসা সামগ্রী</p>
</header>

<nav>
  <a href="#products">পণ্যসমূহ</a>
  <a href="#contact">যোগাযোগ</a>
</nav>

<div class="container">
  <section id="products">
    <h2>আমাদের পণ্য</h2>
    <div class="product">
      <h3>Antibiotic ইনজেকশন</h3>
      <p>গরুর ইনফেকশন প্রতিরোধে ব্যবহৃত হয়।</p>
      <p><strong>মূল্যঃ</strong> ২০০ টাকা</p>
    </div>
    <div class="product">
      <h3>ভিটামিন সিরাপ</h3>
      <p>গরুর স্বাস্থ্য ও ওজন বৃদ্ধির জন্য উপকারী।</p>
      <p><strong>মূল্যঃ</strong> ১৫০ টাকা</p>
    </div>
    <div class="product">
      <h3>কৃমিনাশক ট্যাবলেট</h3>
      <p>পেটের কৃমি দূর করতে ব্যবহৃত হয়।</p>
      <p><strong>মূল্যঃ</strong> ৫০ টাকা</p>
    </div>
  </section>

  <section id="contact">
    <h2>যোগাযোগ করুন</h2>
    <form onsubmit="submitForm(); return false;">
      <input type="text" placeholder="আপনার নাম" required>
      <input type="email" placeholder="আপনার ইমেইল" required>
      <textarea placeholder="আপনার বার্তা" rows="4" required></textarea>
      <button type="submit">পাঠান</button>
    </form>
  </section>
</div>

<footer>
  &copy; ২০২৫ গরুর ওষুধের দোকান | সমস্ত অধিকার সংরক্ষিত
</footer>

<script>
  function submitForm() {
    alert("ধন্যবাদ! আপনার বার্তাটি পাঠানো হয়েছে।");
  }
</script>

</body>
</html>
