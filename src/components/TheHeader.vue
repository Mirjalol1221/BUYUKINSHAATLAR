<template>
  <video id="background-video" autoplay loop muted>
    <source src="../assets/images/home-video.mp4" type="video/mp4" />
  </video>
  <section class="head">
    <div class="container">
      <div class="head-text">
        <h1><span>BUYUK INSHAATLAR</span> ENG ZO`R SIFAT ISTAGANLAR UCHUN</h1>
      </div>
      <p>MAXSUS USULDA TOBLANGAN VA HIMOYA QOPLAMIGA EGA</p>
      <div class="btn">
        <button>BATAFSIL MA`LUMOT</button>
      </div>
    </div>
  </section>
</template>

<style>
video {
  width: 100%;
  height: 100vh;
  object-fit: cover;
  position: absolute;
  z-index: -1;
}

.head {
  width: 100%;
  height: 100vh;
  padding: 0 30px;
}

.head .container .head-text {
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 180px;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}

.head .container .head-text h1 {
  max-width: 900px;
  font-size: 75px;
  line-height: 80px;
  text-align: center;
  color: #fff;
}

.head .container .head-text h1 span {
  color: #03adfc;
}

.head .container p {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  max-width: 700px;
  margin: 20px auto 0;
  color: #fff;
}

.head .container .btn {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 30px;
}

.head .container .btn button {
  width: 200px;
  height: 60px;
  cursor: pointer;
  background: #03adfc;
  color: #fff;
  border: 0;
  font-size: 16px;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  box-shadow: inset 0 0 20px rgba(255, 255, 255, 0);
  outline: 1px solid;
  outline-color: rgba(255, 255, 255, 0.5);
  outline-offset: 0px;
  text-shadow: none;
  transition: all 1250ms cubic-bezier(0.19, 1, 0.22, 1);
}

.head .container .btn button:hover {
  border: 1px solid;
  box-shadow: inset 0 0 20px rgba(255, 255, 255, 0.5);
  outline-offset: 15px;
  text-shadow: 2px 2px 4px #fff;
}

.head .container .head-text h1 {
  font-size: 50px;
}

.head .container p {
  font-size: 16px;
}

/* Medium screens (max-width: 1500px) */
@media (max-width: 1500px) {
  .head .container .head-text h1 {
    font-size: 45px;
  }

  .head .container p {
    font-size: 13px;
  }
}

/* Small screens (max-width: 768px) */
@media screen and (max-width: 768px) {
.head{
  height: 60vh;
}

  .head .container .head-text {
    display: flex;
    justify-content: center;
    padding-top: 120px;
  }

  .head .container .head-text h1 {
    font-size: 30px;
    line-height: 1.2;
  }

  .head .container p {
    font-size: 13px;
    text-align: center;
  }

  .head .container .btn button {
    font-size: 12px;
    width: 120px;
    height: 40px;
  }
}

/* Extra small screens (max-width: 505px) */
@media (max-width: 505px) {
  video,
  .head {
    height: 60vh;
  }

  .head .container .head-text h1 {
    font-size: 30px;
  }

  .head .container p {
    font-size: 8px;
  }
}

/* Tiny screens (max-width: 350px) */
@media (max-width: 350px) {
  .head {
    height: 60vh;
  }

  .head .container p {
    display: none;
  }

  .head .container .head-text h1 {
    font-size: 25px;
    line-height: 1.4;
  }

  .head .container .btn button {
    font-size: 9px;
    width: 90px;
    height: 30px;
  }
}
</style>
