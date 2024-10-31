<template>
  <!-- Page content -->
  <div class="content ">

    <!-- Automatic Slideshow Images -->
    <div class="mySlides display-container center">
      <img src="https://www.w3schools.com/w3images/la.jpg" style="width:100%">
      <div class="display-bottommiddle container text-white padding hide-small">
        <h3>Los Angeles</h3>
        <p style="color: aliceblue;"><b>We had the best time playing at Venice Beach!</b></p>
      </div>
    </div>
    <div class="mySlides display-container center">
      <img src="https://www.w3schools.com/w3images/ny.jpg" style="width:100%">
      <div class="display-bottommiddle container text-white padding hide-small">
        <h3>New York</h3>
        <p style="color: aliceblue;"><b>The atmosphere in New York is lorem ipsum.</b></p>
      </div>
    </div>
    <div class="mySlides display-container center">
      <img src="https://www.w3schools.com/w3images/chicago.jpg" style="width:100%">
      <div class="display-bottommiddle container text-white padding hide-small">
        <h3>Chicago</h3>
        <p style="color: aliceblue;"><b>Thank you, Chicago - A night we won't forget.</b></p>
      </div>
    </div>

    <!-- The Band -->
    <div class="container content center padding" id="band" style="max-width: 800px;">
      <h2 class="wide">THE BAND</h2>
      <p class="opacity" ><i>We love music</i></p>
      <p class="justify">We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing
        elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco laboris nisi ut aliquip
        ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat
        nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim
        id est laborum consectetur
        adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      <div class="row padding-32">
        <div class="third">
          <p>Name</p>
          <img src="https://www.w3schools.com/w3images/bandmember.jpg" class="round margin-bottom" alt="Random Name"
            style="width:60%">
        </div>
        <div class="third">
          <p>Name</p>
          <img src="https://www.w3schools.com/w3images/bandmember.jpg" class="round margin-bottom" alt="Random Name"
            style="width:60%">
        </div>
        <div class="third">
          <p>Name</p>
          <img src="https://www.w3schools.com/w3images/bandmember.jpg" class="round" alt="Random Name"
            style="width:60%">
        </div>
      </div>
    </div>

    <!-- The Tour -->
    <div class="black" id="tour">
      <div class="container content padding" style="max-width:800px">
        <h2 class="wide center">TOUR DATES</h2>
        <p style="color: #838383;" class="opacity center"><i>Remember to book your tickets!</i></p><br>

        <ul class="ul border white text-grey">
          <li style="color: black;" class="padding">September <span class="tag red margin-left">Sold out</span></li>
          <hr>
          <li style="color: black;" class="padding">October <span class="tag red margin-left">Sold out</span></li>
          <hr>
          <li class="padding" style="color: black; display: flex; justify-content: space-between; align-items: center;">
            November <span class="badge right margin-right">3</span>
          </li>
        </ul>


        <div class="row-padding padding-32">

          <div class="third-tour margin-bottom">
            <img src="https://www.w3schools.com/w3images/newyork.jpg" alt="New York"
              style="width:100%; background-color: aliceblue;" class="hover-opacity">
            <div class="container white">
              <p><b>New York</b></p>
              <p class="opacity">Fri 27 Nov 2016</p>
              <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
              <button class="button-tour black margin-bottom"
                onclick="document.getElementById('ticketModal').style.display='block'">Buy Tickets</button>
            </div>
          </div>
          <div class="third-tour margin-bottom">
            <img src="https://www.w3schools.com/w3images/paris.jpg" alt="Paris" style="width:100%"
              class="hover-opacity">
            <div class="container white">
              <p><b>Paris</b></p>
              <p class="opacity">Sat 28 Nov 2016</p>
              <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
              <button class="button-tour black margin-bottom"
                onclick="document.getElementById('ticketModal').style.display='block'">Buy Tickets</button>
            </div>
          </div>
          <div class="third-tour margin-bottom">
            <img src="https://www.w3schools.com/w3images/sanfran.jpg" alt="San Francisco" style="width:100%"
              class="hover-opacity">
            <div class="container white">
              <p><b>San Francisco</b></p>
              <p class="opacity">Sun 29 Nov 2016</p>
              <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
              <button class="button-tour black margin-bottom"
                onclick="document.getElementById('ticketModal').style.display='block'">Buy Tickets</button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- trong nút buy Ticket -->
    <div id="ticketModal" class="modal">
      <div class="modal-content animate-top card">
        <header class="container teal center padding-32">
          <span onclick="document.getElementById('ticketModal').style.display='none'"
            class="button teal xlarge display-topright">&times;</span>
          <h2 class="wide"><i class="fa fa-suitcase margin-right"></i>Tickets</h2>
        </header>
        <div class="container">
          <p><label><i class="fa fa-shopping-cart"></i> Tickets, $15 per person</label></p>
          <input class="input border" type="text" placeholder="How many?">
          <p><label><i class="fa fa-user"></i> Send To</label></p>
          <input class="input border" type="text" placeholder="Enter email">
          <button class="button block teal padding-16 section right">PAY <i class="fa fa-check"></i></button>
          <button class="button red section"
            onclick="document.getElementById('ticketModal').style.display='none'">Closeborder
            <i class="fa fa-remove"></i></button>
          <p style="text-align: right;" class="right">Need <a href="#" class="text-blue">help?</a></p>
        </div>
      </div>
    </div>

    <!-- The Contact -->
    <div class="contact-container" id="contact">
      <h2 class="contact-title">CONTACT</h2>
      <p class="contact-subtitle"><i>Fan? Drop a note!</i></p>
      <div class="contact-row">
        <div class="contact-info" style="text-align: left">
          <i class="fa fa-map-marker"></i> Chicago, US<br>
          <i class="fa fa-phone"></i> Phone: +00 151515<br>
          <i class="fa fa-envelope"></i> Email: mail@mail.com<br>
        </div>
        <div class="contact-form">
          <form action="/action_page.php" method="post" target="_blank">
            <div class="form-row">
              <div class="form-group">
                <input class="form-input" type="text" placeholder="Name" required name="Name">
              </div>
              <div class="form-group">
                <input class="form-input" type="email" placeholder="Email" required name="Email">
              </div>
            </div>
            <input class="form-input" type="text" placeholder="Message" required name="Message">
            <div class="button-container">
              <button class="form-button" type="submit">SEND</button>
            </div>
          </form>
        </div>
      </div>
    </div>


  </div>
  <!-- Image of location/map -->
  <img src="https://www.w3schools.com/w3images/map.jpg" class="w3-image w3-greyscale-min" style="width:100%">
</template>


<script>
export default {
  name: 'BodyS',
  mounted() {
    this.showSlides();
  },
  methods: {
    showSlides() {
      let myIndex = 0;
      const slides = document.getElementsByClassName("mySlides");
      const showNextSlide = () => {
        for (let i = 0; i < slides.length; i++) {
          slides[i].style.display = "none";
        }
        myIndex++;
        if (myIndex > slides.length) { myIndex = 1 }
        slides[myIndex - 1].style.display = "block";
        setTimeout(showNextSlide, 4000); // Change image every 4 seconds
      };
      showNextSlide();
    }
  }
};
</script>

<style scope>
/* Đặt margin cho body và reset */
body {
  margin: 0;
  /* loại bỏ khoảng cách mặc định của trình duyệt */
  font-family: "Lato", sans-serif;
  /* Đặt kiểu chữ cho văn bản trong body là "Lato" và nếu không có thì sử dụng kiểu chữ sans-serif */
}

.container {
  margin: auto;
}

.container.content {
  padding: 64px 16px;
}

.mySlides {
  position: relative;
  /* Để nội dung con có thể đặt vị trí tuyệt đối */
}

/* Đặt chữ ở giữa dưới mỗi ảnh */
.display-bottommiddle {
  position: absolute;
  bottom: 10%;
  /* Điều chỉnh vị trí chữ từ dưới lên */
  left: 10%;
  /* cách trái 10% */
  color: white;
  /* Màu chữ */
  width: 80%;
  /* Chiều rộng của khung chữ */
}

h2 {
  font-family: "Segoe UI", Arial, sans-serif;
  font-weight: 400;
  margin: 10px 0;
}
.opacity{
  opacity: 0.7;
}
/* Tăng cường độ tương phản cho chữ */
h3,
p {
  color: white;
}

h3 {
  font-family: "Segoe UI", Arial, sans-serif;
  font-size: 24px;
  font-weight: 400;
  margin: 10px 0;
}

p {
  font-size: 16px;
  color: black;
}


.justify {
  color: #000;
  text-align: justify;
  /* Căn chỉnh văn bản trong the band sao cho đều hai bên */
  margin: 15px 0px;
  /* Đặt khoảng cách bên ngoài (margin) cho class .justify là 15px ở trên và dưới, 0px ở hai bên */
}

/* Căn chỉnh hàng */
.row {
  display: flex;
  /* Sử dụng Flexbox để sắp xếp trong cùng một hàng  */
  /* Nếu không đủ chỗ để chứa tất cả các phần tử trong một hàng, các phần tử sẽ chuyển xuống hàng kế tiếp */
}

/* the tour */
.third-tour {
  flex: 30%;
  /* Đặt chiều rộng của mỗi phần tử là 30% */
  float: left;
  margin: 10px;
  /* Tạo khoảng cách giữa các phần tử */
  padding: 0px;
  background-color: #FFFFFF;

}

/* tour */
.contaier.white {
  padding-left: 0.15px 16px;

}

h2.wide.center {
  font-family: "Segoe UI", Arial, sans-serif;
  font-weight: 400;
  margin: 10px 0;
}

.justify {
  color: #000;
  text-align: justify;
  margin: 15px 0px;
}

.button-tour {
  font-size: 15px;
  padding: 10px 20px;
  /* Thêm khoảng cách bên trong nút */
  padding-left: 16px;
  background-color: black;
  /* Màu nền nút */
  color: white;
  /* Màu chữ */
  border: none;
  /* Xóa viền nút */
  cursor: pointer;
  /* Hiển thị con trỏ chuột như là tay khi di chuột qua nút */
  margin: 0px 0px 16px;
  /* Thêm khoảng cách 10px ở trên và dưới nút */

}

.button-tour:hover {
  color: black;
  background-color: #CCCCCC;
  /* Màu nền khi hover */
}

/* Căn giữa và điều chỉnh layout cho phần "The Tour" */
.row-padding {
  display: block;
  display: flex;
  justify-content: center;
  /* Căn giữa tất cả các phần tử */
  flex-wrap: wrap;
  margin: 0px -16px;
  padding: 32px 8px;
}

/* Tour */
/* Nền đỏ và chữ trắng cho thông báo Sold out */
.tag.red {
  background-color: #F44336;
  /* Nền đỏ */
  color: white;
  /* Chữ trắng */
  padding: 0px 10px;
  margin: 0px 0px 0px 16px;
}

/* Căn trái cho các thẻ  chỉnh tron ảnh tour*/
.container.white {
  border-radius: 5px;
  /* Đặt độ bo tròn */
  padding: 10px;
  /* Thêm khoảng cách bên trong */
  margin: 5px 0;
  /* Thêm khoảng cách giữa các đoạn văn */
  text-align: left;
  /* Căn trái */
  color: black;
  /* Màu chữ đen cho các thẻ <p> */
}

/* Căn trái cho các phần tử <li> trong danh sách */
.ul li {
  text-align: left;
  /* Căn trái cho các thẻ <li>*/
  color: black;
  /* Màu chữ đen */
}

/* Đặt màu chữ cho các thông báo '3' tour*/
.badge.right {
  background-color: black;
  /* Màu nền cho số lượng vé */
  color: white;
  /* Chữ trắng */
  padding: 5px 10px;
  border-radius: 50%;
}

.third {
  flex: 0 0 30%;
  /* Đặt chiều rộng của mỗi phần tử là 30% */
  margin: 0 10px;
  /* Tạo khoảng cách giữa các phần tử */
  text-align: center;
  /* Căn giữa nội dung */
  padding: 32px 0px;

}


/* Màu nền đen và chữ trắng */
.black {
  background-color: black;
  color: white;
}

.text-grey {
  color: white;
}

.ul {
  background-color: white;
  padding: 10px;
}

.padding {
  padding: 16px;
}

/* Điều chỉnh cho button */
.button {
  border: none;
  padding: 10px 20px;
  border-radius: 4px;
  cursor: pointer;
  /* Khi di chuyển con trỏ chuột qua phần tử được áp dụng thuộc tính này, nó sẽ chuyển sang hình dạng bàn tay */
}

.button:hover {
  opacity: 0.8;
  /* Giảm độ mờ của nút xuống còn 80% khi người dùng di chuột qua */
}

/* Thiết kế form trong phần liên hệ */
.input {

  border: 1px solid #ccc;
  /* Viền mỏng, màu xám nhạt */

}

/* Đặt modal */
.modal {
  display: none;
  /* Ẩn modal theo mặc định */
  position: fixed;
  /* Đặt modal ở vị trí cố định trên màn hình */
  top: 0;
  /* Bắt đầu từ đỉnh của trang */
  width: 100%;
  /* Chiếm toàn bộ chiều rộng của màn hình */
  height: 100%;
  /* Chiếm toàn bộ chiều cao của màn hình */
  background-color: rgba(0, 0, 0, 0.5);
  /* Nền màu đen với độ trong suốt 50% */
  overflow: auto;
  /* Thêm thanh cuộn nếu nội dung quá lớn để hiển thị */
}

.modal-content {
  background-color: white;
  /* Nền của nội dung modal là màu trắng */
  margin: 10% auto;
  /* Khoảng cách từ trên cùng là 10%, tự động căn giữa theo chiều ngang */
  padding: 20px;
  /* Khoảng cách bên trong nội dung modal là 20px */
  border: 1px solid #888;
  /* Viền màu xám vừa phải */
  width: 80%;
  /* Chiều rộng của nội dung modal chiếm 80% chiều rộng màn hình */
  border-radius: 8px;
  /* Bo tròn góc viền của modal nội dung với bán kính 8px */
}


#band {
  max-width: 800px;
  /* Giới hạn chiều rộng */
  margin: auto;
  /* căn trên dưới và Căn giữa */
  padding: 64px 16px;
  /* Thêm khoảng đệm (khoảng cách giữa viền và nội dung bên trong)*/


}

/* contact */
* {
  box-sizing: border-box;
  /* Ensures padding is included in width calculations */
}

.contact-container {
  max-width: 800px;
  margin: auto;
  padding: 64px;
}

.contact-title {
  color: #000000;
  font-family: "Segoe UI", Arial, sans-serif;
  text-align: center;
  font-size: 30px;
  margin: 10px 0px;
  font-weight: 400;
}

.contact-subtitle {
  text-align: center;
  color: #000000;
  opacity: 0.5;
}

.contact-row {
  display: flex;
  padding: 32px 0;
}

.contact-info {
  flex: 1;
  font-size: 18px;
  margin-bottom: 16px;
}

.contact-info i {
  width: 30px;
  vertical-align: middle;
}

.contact-form {
  flex: 1;
}

.form-row {
  display: flex;
  margin: 0 -8px 8px;
}

.form-group {
  flex: 1;
  /* Each group takes equal space */
  padding: 0 8px;
}

.form-input {
  width: 100%;
  /* Ensure input takes full width of the group */
  padding: 12px;
  border: 1px solid #ccc;
  margin-bottom: 16px;
}

.button-container {
  display: flex;
  justify-content: flex-end;
  /* Aligns the button to the right */
}

.form-button {
  background-color: black;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

.form-button:hover {
  background-color: #333;
  /* Darker shade on hover */
}


/* Trong nút ticket */
/* Màu nền cho header modal */
#ticketModal .modal-content .container.teal {
  background-color: #009688;
  /* Màu nền cho header */
  color: #ccc;
  text-align: center;
  /* Căn giữa nội dung */
  padding: 16px 0;
  /* Thêm khoảng cách trên và dưới */
}

/* Đặt khoảng cách cho tiêu đề trong header */
#ticketModal .modal-content .container.teal h2 {
  margin: 20px 0;
  /* Khoảng cách trên và dưới cho tiêu đề */
}

#ticketModal .container {
  text-align: left;
  /* Căn trái văn bản */
}

/* Nút PAY */
#ticketModal .button.block.teal {
  width: 100%;
  /* Đặt chiều rộng của nút PAY bằng 100% */
  background-color: #009688;
  /* Màu nền cho nút PAY */
  color: white;
  /* Đặt màu chữ trắng cho nút */
}

/* Định dạng nút Close */
#ticketModal .modal-content .button.red.section {
  background-color: red;
  /* Màu nền đỏ cho nút Close */
  color: white;
  /* Màu chữ trắng cho nút Close */
  width: auto;
  /* Để chiều rộng tự động */
  margin-top: 20px;
  /* Thêm khoảng cách trên nút Close */
}

/* Thay đổi màu nền khi di chuột lên nút PAY */
#ticketModal .button.block.teal:hover {
  background-color: #00796b;
  /* Màu tối hơn khi di chuột lên */
}
</style>