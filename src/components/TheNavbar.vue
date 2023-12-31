<template>
  <div class="navbar">
    <div class="container">
      <div class="nav">
        <div class="logo">
          <img src="../assets/images/logo-2.png" alt="" />
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="30"
            width="30"
            viewBox="0 0 512 512"
          >
            <!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2023 Fonticons, Inc.-->
            <path
              fill="#03adfc"
              d="M164.9 24.6c-7.7-18.6-28-28.5-47.4-23.2l-88 24C12.1 30.2 0 46 0 64C0 311.4 200.6 512 448 512c18 0 33.8-12.1 38.6-29.5l24-88c5.3-19.4-4.6-39.7-23.2-47.4l-96-40c-16.3-6.8-35.2-2.1-46.3 11.6L304.7 368C234.3 334.7 177.3 277.7 144 207.3L193.3 167c13.7-11.2 18.4-30 11.6-46.3l-40-96z"
            />
          </svg>
          <span>33 446 49 49</span>
        </div>
        <ul>
          <li>KOMPANIYA HAQIDA</li>
          <li>BIZNING LOYIHALARIMIZ</li>
          <li>MAHSULOTLAR</li>
          <li>YANGILIKLAR</li>
          <li>ALOQA</li>
        </ul>
        <div class="btn">
          <button>BEPUL MASLAHAT</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.navbar {
  position: fixed;
  background: #0e0e0e;
  width: 100%;
  height: 70px;
  padding: 0 10px;
}

.navbar .container {
  max-width: 1440px;
  margin: 0 auto;
}

.navbar .container .nav {
  display: flex;
  justify-content: space-between;
}

.navbar .container .nav .logo {
  display: flex;
  align-items: center;
  gap: 20px;
  margin-top: -5px;
}

.navbar .container .nav .logo img {
  width: 85px;
  height: 85px;
}

.navbar .container .nav .logo span {
  font-size: 25px;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  color: #fff;
  cursor: pointer;
}

.navbar .container .nav ul {
  color: #fff;
  list-style: none;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 15px;
  display: flex;
  align-items: center;
  gap: 25px;
  cursor: pointer;
}

.navbar .container .nav ul li:hover {
  border-bottom: 1.5px #03adfc solid;
  transition: 1s;
}

.navbar .container .nav .btn button {
  width: 200px;
  height: 40px;
  background: #03adfc;
  color: #fff;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  border: 0;
  margin-top: 15px;
  border-radius: 50px;
  cursor: pointer;
  font-size: 15px;
}

.navbar .container .nav .btn button:hover {
  background: #16b5ff;
  transition: 0.5s;
}

@media (max-width: 1250px) {
  .navbar .container .nav ul {
    display: none;
  }
}

@media (max-width: 700px) {
  .navbar .container .nav .btn button,
  .navbar .container .nav .logo svg,
  .navbar .container .nav .logo span {
    display: none;
  }
}
</style>
