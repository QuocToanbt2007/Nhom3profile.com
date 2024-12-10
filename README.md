
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PROFILE NHÓM 3</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #d2b48c, #ffffff); /* Nền nâu nhạt chuyển thành trắng */
        }
        .header {
            background-color: #d2b48c; /* Màu nâu nhạt */
            padding: 20px;
            text-align: center;
            color: #fff;
            font-size: 2em;
            font-weight: bold;
        }
        .content {
            text-align: center;
            padding: 20px;
        }
        .content img {
            width: 80%;
            max-width: 500px;
            margin: 10px 0;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        hr {
            width: 80%;
            border: 1px solid #000;
            margin: 20px auto;
        }
        .gallery {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }
        .gallery img {
            width: 100px;
            height: 100px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .form-container {
            margin-top: 30px;
            text-align: center;
        }
        .form-container form {
            display: inline-block;
            background-color: #f8f8f8;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .form-container input, .form-container textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container button {
            background-color: #d2b48c; /* Nâu nhạt */
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .form-container button:hover {
            background-color: #a88e6e; /* Màu nâu đậm hơn */
        }
        .thank-you {
            text-align: center;
            font-size: 1.5em;
            margin-top: 30px;
            color: #006400; /* Màu xanh lá đậm */
        }
    </style>
</head>
<body>

    <!-- Pano đầu trang -->
    <div class="header">
        PROFILE NHÓM 3 
    </div>

    <!-- Ảnh và văn bản -->
    <div class="content">
        <img src="https://short.com.vn/i5ht" alt="Hình ảnh chính">
        <p> Chào mừng đến với trang web nhóm 3, bạn có thể tiềm kiếm thông tin về các thành viên tại đây.</p>
    </div>

    <!-- Dấu gạch ngang -->
    <hr>

    <!-- Bộ sưu tập ảnh và đường dẫn -->
    <div class="gallery">
        <a href="https://short.com.vn/8L8e">
            <img src="https://s.pro.vn/hcoR" alt="Thiên Ân">
        </a>
        <a href="https://s.pro.vn/cOoX">
            <img src="https://short.com.vn/VPwa" alt="Gia Bảo">
        </a>
        <a href="https://s.pro.vn/bfAN">
            <img src="https://s.pro.vn/Aoi0" alt="	Trọng Duy">
        </a>
        <a href="https://short.com.vn/3kZY">
            <img src="https://s.pro.vn/LNg7" alt="Quốc Toản">
        </a>
    </div>

    <!-- Biểu mẫu điền thông tin -->
    <div class="form-container">
        <h2>Điền thông tin của bạn</h2>
        <form action="#" method="POST">
            <input type="text" name="fullname" placeholder="Họ tên" required><br>
            <input type="email" name="email" placeholder="Email" required><br>
            <input type="tel" name="phone" placeholder="Số điện thoại" required><br>
            <textarea name="message" placeholder="Lời nhắn (tùy chọn)"></textarea><br>
            <button type="submit">Gửi Thông Tin</button>
        </form>
    </div>

    <!-- Lời cảm ơn -->
    <div class="thank-you">
        Cảm ơn bạn đã ghé thăm trang web của nhóm 3!
    </div>

</body>
</html>
