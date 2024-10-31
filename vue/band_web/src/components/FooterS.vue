<template>
    <footer class="footer">
      <i class="fa fa-facebook-square social-icon"></i>
      <i class="fa fa-instagram social-icon"></i>
      <i class="fa fa-snapchat social-icon"></i>
      <i class="fa fa-pinterest-p social-icon"></i>
      <i class="fa fa-twitter social-icon"></i>
      <i class="fa fa-linkedin social-icon"></i>
      <p class="footer-text">Powered by <a href="https://www.w3schools.com/w3css/default.asp">w3.css</a></p>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    background-color: #f0f0f0; /* Màu nền xám nhạt */
    padding: 64px 20px; /* Khoảng cách bên trong */
    text-align: center; /* Căn giữa nội dung */
    opacity: 0.8; /* Độ mờ của footer */
    font-size: 24px; /* Kích thước chữ lớn */
  }
  
  /* Các biểu tượng xã hội */
  .social-icon {
    font-size: 30px; /* Kích thước biểu tượng lớn */
    margin: 0px 10px; /* Khoảng cách giữa các biểu tượng */
    color: #333; /* Màu chữ tối */
  }
  
  /* Hiệu ứng hover cho các biểu tượng */
  .social-icon:hover {
    color: #007bff; /* Màu khi hover */
  }
  
  /* Text footer */
  .footer-text {
    margin-top: 20px; /* Khoảng cách trên text */
    font-size: 16px; /* Kích thước chữ vừa */
    color: #555; /* Màu chữ xám */
  }
  
  /* Đường link trong footer */
  .footer-text a {
    color: #007bff; /* Màu link */
    text-decoration: none; /* Bỏ gạch chân */
  }
  
  /* Hiệu ứng hover cho link */
  .footer-text a:hover {
    text-decoration: underline; /* Gạch chân khi hover */
  }
  </style>
  