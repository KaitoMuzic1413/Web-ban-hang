<!-- HTML -->
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <meta name="description" content="Kaito coder."> 
  <meta name="author" content="Kaito Kid"> 
  <meta name="keywords" content="Kaito, kaito, kaito kid, kid, Kid, coder, code, html, lajajp trình"> 
  <title>Coder</title>  
  <link rel="icon" href="favicon.ico" type="image/x-icon"> 
  <script src="script.js" defer></script> 
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"> 
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"> 
  <meta property="og:title" content="Tiêu đề khi chia sẻ"> 
  <meta property="og:description" content="Miêu tả khi chia sẻ"> 
  <meta property="og:image" content="link-to-image.jpg"> 
  <meta property="og:url" content="https://example.com"> 
  <meta name="robots" content="index, follow"> 
  <title>Shop của Thái</title> 
  <style>
    /* Css */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: inherit;
    border: inherit;
}

header {
    background: #007bff;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin-bottom: 0.5rem;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

nav ul li {
    display: inline-block; /* Giữ dạng nút */
    border: 2px solid blue;
    margin: 5px;
    padding: 10px 20px;
    border-radius: 25px;
    background-color: white;
    transition: transform 0.3s ease-in-out, background-color 0.3s ease;
}

nav ul li a {
    display: block; /* Giúp toàn bộ nút có thể bấm được */
    color: blue;
    text-decoration: none;
    font-weight: bold;
    padding: 10px 20px; /* Giúp dễ bấm hơn */
}

nav ul li:hover {
    transform: scale(1.2);
    background-color: lightblue;
}

.section {
    padding: 2rem;
    min-height: 100vh;
    text-align: center;
    border-bottom: 1px solid #ddd;
}

#home {
    background: #f4f4f4;
    border: 1px solid blue;
    
}



#products {
    background: #fff3cd;
    border: px solid blue;
}

#contact {
    background: #d1e7dd;
    border: 1px solid blue;
}

.product-list {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 1rem;
}

.product {
    border: 1px double #ddd;
    padding: 1rem;
    text-align: center;
    border-radius: 5px;
    width: 200px;
    background: #fff;
}



.product img {
    max-width: 100%;
    border-radius: 5px;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
}

form input, form textarea {
    width: 300px;
    padding: 0.5rem;
    border: 1px solid #ddd;
    border-radius: 3px;
}

form button {
    background: #007bff;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
    border-radius: 3px;
}

form button:hover {
    background: #0056b3;
}

.btn-facebook {
  display: inline-block;
  padding: 10px 20px;
  color: white;
  background-color: #007bff;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  text-align: center;
}

.btn-facebook:hover {
  background-color: #306b3;
}

.ytb {
  display: inline-block;
  padding: 10px 20px;
  color: white;
  background-color: #007bff;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  text-align: center;
}

.ytb:hover {
  background-color: #306b3;
}

.x {
  display: inline-block;
  padding: 10px 20px;
  color: white;
  background-color: #007bff;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  text-align: center;
}

.x:hover {
  background-color: #306b3;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

nav ul li {
    border: 2px solid blue; /* Viền xanh */
    margin: 5px;
    padding: 10px 20px; /* Tăng kích thước cho dễ bấm */
    border-radius: 25px; /* Bo tròn */
    background-color: white; /* Nền trắng */
    transition: transform 0.3s ease-in-out, background-color 0.3s ease; /* Hiệu ứng mượt */
}

nav ul li a {
    color: blue;
    text-decoration: none;
    font-weight: bold;
}

nav ul li:hover {
    transform: scale(1.2); /* Phóng to */
    background-color: lightblue; /* Đổi màu khi hover */
}/* Css */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: inherit;
    border: inherit;
}

header {
    background: #007bff;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin-bottom: 0.5rem;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

nav ul li {
    display: inline-block; /* Giữ dạng nút */
    border: 2px solid blue;
    margin: 5px;
    padding: 10px 20px;
    border-radius: 25px;
    background-color: white;
    transition: transform 0.3s ease-in-out, background-color 0.3s ease;
}

nav ul li a {
    display: block; /* Giúp toàn bộ nút có thể bấm được */
    color: blue;
    text-decoration: none;
    font-weight: bold;
    padding: 10px 20px; /* Giúp dễ bấm hơn */
}

nav ul li:hover {
    transform: scale(1.2);
    background-color: lightblue;
}

.section {
    padding: 2rem;
    min-height: 100vh;
    text-align: center;
    border-bottom: 1px solid #ddd;
}

#home {
    background: #f4f4f4;
    border: 1px solid blue;
    
}



#products {
    background: #fff3cd;
    border: px solid blue;
}

#contact {
    background: #d1e7dd;
    border: 1px solid blue;
}

.product-list {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 1rem;
}

.product {
    border: 1px double #ddd;
    padding: 1rem;
    text-align: center;
    border-radius: 5px;
    width: 200px;
    background: #fff;
}



.product img {
    max-width: 100%;
    border-radius: 5px;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
}

form input, form textarea {
    width: 300px;
    padding: 0.5rem;
    border: 1px solid #ddd;
    border-radius: 3px;
}

form button {
    background: #007bff;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
    border-radius: 3px;
}

form button:hover {
    background: #0056b3;
}

.btn-facebook {
  display: inline-block;
  padding: 10px 20px;
  color: white;
  background-color: #007bff;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  text-align: center;
}

.btn-facebook:hover {
  background-color: #306b3;
}

.ytb {
  display: inline-block;
  padding: 10px 20px;
  color: white;
  background-color: #007bff;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  text-align: center;
}

.ytb:hover {
  background-color: #306b3;
}

.x {
  display: inline-block;
  padding: 10px 20px;
  color: white;
  background-color: #007bff;
  text-decoration: none;
  border-radius: 5px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  text-align: center;
}

.x:hover {
  background-color: #306b3;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

nav ul li {
    border: 2px solid blue; /* Viền xanh */
    margin: 5px;
    padding: 10px 20px; /* Tăng kích thước cho dễ bấm */
    border-radius: 25px; /* Bo tròn */
    background-color: white; /* Nền trắng */
    transition: transform 0.3s ease-in-out, background-color 0.3s ease; /* Hiệu ứng mượt */
}

nav ul li a {
    color: blue;
    text-decoration: none;
    font-weight: bold;
}

nav ul li:hover {
    transform: scale(1.2); /* Phóng to */
    background-color: lightblue; /* Đổi màu khi hover */
}
  </style>
 </head> 
 <body> 
  <header> 
   <h1>Shop của Thái</h1> 
   <nav> 
    <ul> 
     <li><a href="#home">Trang Chủ</a></li> 
     <li><a href="#products">Sản Phẩm</a></li> 
     <li><a href="#contact">Liên Hệ</a></li> 
    </ul> 
   </nav> 
  </header> 
  <main> 
   <section id="home" class="section"> 
    <h2>Trang Chủ</h2> 
    <p>Chào mừng bạn đến với Shop của Thái!</p> 
    <p>Chúng tôi chuyên cung cấp các loại tập chất lượng cao.</p> 
    <p><strong>Thông tin nổi bật:</strong></p> 
    <ul> 
     <li>Ưu đãi giảm giá tới 50% dịp Tết Nguyên Đán!</li> 
     <li>Hàng mới về: tập 4 ô li 100 trang, tập 5 ô li 200 trang, tập 4 ô li 200 trang size lớn, và nhiều hơn nữa!</li> 
    </ul> 
   </section> 
   <section id="products" class="section"> 
    <h2>Sản Phẩm</h2> 
    <p><strong>Sản phẩm hot:</strong></p> 
    <div class="product-list"> 
     <div class="product"> 
      <h3>Sản phẩm 1</h3> 
      <p>Giá: 4.000đ</p> 
     </div> 
     <div class="product"> 
      <h3>Sản phẩm 2</h3> 
      <p>Giá: 9.000đ</p> 
     </div> 
     <div class="product"> 
      <h3>Sản phẩm 3</h3> 
      <p>Giá: 14.000đ</p> 
     </div> 
    </div> 
   </section> 
   <section id="contact" class="section"> 
    <h2>Liên Hệ</h2> 
    <p>Hãy gửi tin nhắn cho chúng tôi nếu bạn có bất kỳ câu hỏi nào:</p> 
    <form> <label for="name">Họ và Tên:</label> 
     <input type="text" id="name" name="name" required> <label for="email">Email:</label> 
     <input type="email" id="email" name="email" required> <label for="message">Tin Nhắn:</label> <textarea id="message" name="message" rows="4"></textarea> <button type="submit">Gửi</button> 
    </form> 
    <p>Bản quyền thuộc về Shop của Thái.</p> 
   </section> 
  </main> 
  <footer> 
   <h4> Liên hệ với tôi. </h4> 
   <ul> 
    <li> <a href="https://www.facebook.com/kaito.muzic?mibextid=kFxxJD" class="btn btn-facebook">Facebook</a> <a href="https://youtube.com/@kaitomuzic?si=skW6adljxY7RM897" class="ytb">Youtube</a> <a href="https://x.com/KaitoMuzic1412?t=2j_SkpdUbXl68vCX62bSTQ&amp;s=09" class="x">X</a> </li> 
   </ul> 
   <p>© 2025 Kaito. All rights reserved.</p> 
  </footer> 
 </body>
</html>
