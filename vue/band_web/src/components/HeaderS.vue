<template>
  <div class="header">
    <div class="navbar">
      <a class="nav-item" href="#" @click="toggleMenu">HOME</a>
      <a class="nav-item" href="#band">BAND</a>
      <a class="nav-item" href="#tour">TOUR</a>
      <a class="nav-item" href="#contact">CONTACT</a>

      <div class="dropdown">
        <button class="dropbtn">MORE</button>
        <div class="dropdown-content">
          <a href="#">Merchandise</a>
          <a href="#">Extras</a>
          <a href="#">Media</a>
        </div>
      </div>

      <a class="nav-item search-icon fa fa-search" href="javascript:void(0)"><i></i></a>
    </div>

    <div id="navDemo" class="mobile-menu" style="display: none;">
      <a class="mobile-item" href="#band" @click="toggleMenu">BAND</a>
      <a class="mobile-item" href="#tour" @click="toggleMenu">TOUR</a>
      <a class="mobile-item" href="#contact" @click="toggleMenu">CONTACT</a>
      <a class="mobile-item" href="#" @click="toggleMenu">MERCH</a>
    </div>
  </div>
</template>


<script>
export default {
  methods: {
    // Hàm toggleMenu điều khiển ẩn/hiện menu điều hướng khi ở chế độ di động
    toggleMenu() {
      // Lấy phần tử #navDemo để thay đổi lớp CSS
      const nav = document.getElementById("navDemo");
      // Nếu chưa có lớp "w3-show", thêm lớp để hiển thị menu
      if (nav.className.indexOf("w3-show") === -1) {
        nav.className += " w3-show";
      } else {
        // Nếu đã có lớp "w3-show", xóa lớp để ẩn menu
        nav.className = nav.className.replace(" w3-show", "");
      }
    }
  }
}
</script>

<style scoped>
.header {
  position: fixed;
  width: 100%;
  background-color: #000000;
  z-index: 999;
  height: 45px;
}

.navbar {
  display: flex;
}

.nav-item {
  color: white;
  text-decoration: none;
  padding: 12px 24px;
}

.nav-item:hover {
  color: #000000;
  background-color: #CCCCCC;

}

/* Nút dropdown */
.dropbtn {
  color: white;
  padding: 12px 24px;
  border: none;
  background-color: #000000;
  font-size: 16px;
}

/* nút more */
.dropbtn:hover {
  color: #000000;
  background-color: #CCCCCC;
}

/* Nội  dropdown */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: white;
}

/* Các mục trong nội dung dropdown */
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown-content a:hover {
  background-color: #CCCCCC;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.search-icon {
  color: white;
  padding: 12px 24px;
  margin-left: auto;
}

.mobile-menu {
  background-color: black;
  padding: 10px;
  position: absolute;
  width: 100%;
}

.mobile-item {
  color: white;
  padding: 10px;
  text-decoration: none;
}

.mobile-item:hover {
  background-color: #555;
}
</style>
<!-- position, flexbox, animation -->