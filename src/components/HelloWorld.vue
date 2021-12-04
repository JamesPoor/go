<template>
  <div class="html">
    <div class="csgo-left">
      <div class="left">
        <img class="logo" src="../assets/img/logo.webp" alt="" />
        <div class="left-svg">
          <a href="#"><img src="../assets/img/discord.svg" alt="" /></a>
        </div>
        <div class="left-svg">
          <a href="#"><img src="../assets/img/twitter.svg" alt="" /></a>
        </div>
        <div class="left-svg">
          <a href="#"><img src="../assets/img/YouTube.svg" alt="" /></a>
        </div>
        <div class="left-svg">
          <a href="#"><img src="../assets/img/facebook.svg" alt="" /></a>
        </div>
        <div class="left-svg">
          <a href="#"><img src="../assets/img/instagram.svg" alt="" /></a>
        </div>
      </div>
    </div>
    <div class="recommend">
      <img class="banner" src="../assets/img/banner.jpg" alt="" />
      <div class="user">
        <img src="../assets/img/user.jpg" alt="" />
        <p class="csgo-recommend">开箱网推荐</p>
        <p class="csgo">高爆率开箱-及时取回秒到账</p>
      </div>
      <div class="csgo-column">
        <a href="#">csgo开箱网</a>
      </div>
      <div class="csgo-middle">
        <div class="middle">
          <div class="csgo-popular">
            <div class="popular-logo">
              <img src="../assets/img/logo.webp" alt="" />
              <a class="goto-rul" href="#"><p class="go-url">立即前往</p></a>
            </div>
            <div class="box-text">
              <p class="csgo-box">xxx开箱网</p>
              <p class="csgo-box-money">新用户注册可获得1～5刀</p>
            </div>
            <div class="popular">
              <div class="csgo-money">
                <img class="money" src="../assets/img/money.svg" alt="" />
                <p class="give-money">+3美刀</p>
              </div>
            </div>
          </div>
          <div class="csgo-popular">
            <div class="popular-logo">
              <img src="../assets/img/logo.webp" alt="" />
              <a class="goto-rul" href="#"><p class="go-url">立即前往</p></a>
            </div>
            <div class="box-text">
              <p class="csgo-box">xxx开箱网</p>
              <p class="csgo-box-money">新用户注册可获得1～5刀</p>
            </div>
            <div class="popular">
              <div class="csgo-money">
                <img class="money" src="../assets/img/money.svg" alt="" />
                <p class="give-money">+3美刀</p>
              </div>
            </div>
          </div>
        </div>
        <div class="middle">
          <div class="csgo-popular">
            <div class="popular-logo">
              <img src="../assets/img/logo.webp" alt="" />
              <a class="goto-rul" href="#"><p class="go-url">立即前往</p></a>
            </div>
            <div class="box-text">
              <p class="csgo-box">xxx开箱网</p>
              <p class="csgo-box-money">新用户注册可获得1～5刀</p>
            </div>
            <div class="popular">
              <div class="csgo-money">
                <img class="money" src="../assets/img/money.svg" alt="" />
                <p class="give-money">+3美刀</p>
              </div>
            </div>
          </div>
          <div class="csgo-popular">
            <div class="popular-logo">
              <img src="../assets/img/logo.webp" alt="" />
              <a class="goto-rul" href="#"><p class="go-url">立即前往</p></a>
            </div>
            <div class="box-text">
              <p class="csgo-box">xxx开箱网</p>
              <p class="csgo-box-money">新用户注册可获得1～5刀</p>
            </div>
            <div class="popular">
              <div class="csgo-money">
                <img class="money" src="../assets/img/money.svg" alt="" />
                <p class="give-money">+3美刀</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  data() {
    return {};
  },
};
</script>

<style scoped>
.html {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: #0a0c10;
}
.banner {
  width: 900px;
  height: 180px;
  position: relative;
  top: -180px;
  border-radius: 10px;
}
.logo {
  width: 64px;
  position: absolute;
  top: -70px;
  left: -6px;
}
.recommend {
  display: flex;
  justify-content: center;
  /* position: absolute;
  top: 200px;
  left: 300px; */
}
.user {
  position: relative;
  top: -170px;
}
.user img {
  border-radius: 50px;
}

.csgo-recommend {
  color: #fff;
  font-size: 26px;
  position: relative;
  left: 120px;
  top: -120px;
}
.csgo {
  color: #fff;
  position: relative;
  top: -130px;
  left: 120px;
}
.csgo-column a {
  color: #fff;
  font-size: 14px;
  position: absolute;
  top: 130px;
  left: 10px;
  text-decoration: none;
  border-bottom: 2px solid #71e4e3;
  padding-bottom: 10px;
}
.popular-logo img {
  width: 64px;
  position: relative;
  left: 260px;
  top: 20px;
}
.goto-rul {
  text-decoration: none;
  text-align: center;
  border-radius: 10px;
  font-size: 14px;
}
.go-url {
  width: 80px;
  height: 25px;
  background-color: #71e4e3;
  padding-top: 5px;
  border-radius: 10px;
  position: relative;
  left: 250px;
  top: 33px;
  color: black;
}
.csgo-popular {
  width: 350px;
  height: 150px;
  margin-right: 200px;
  background-color: #101419;
}
.popular {
  color: #fff;
  background-color: #212832;
  width: 100px;
  height: 31px;
  border: 0;
  border-radius: 10px;
  position: relative;
  bottom: 93px;
  left: 25px;
  font-size: 12px;
}
.csgo-money {
  width: 40px;
  height: 25px;
  /* background-color: #1269d3; */
  background-color: #101419;
  position: absolute;
  left: 5px;
  top: 3px;
  border-radius: 10px;
  z-index: 1;
}
.money {
  width: 32px;
  position: absolute;
  top: -3px;
  left: 3px;
}
.give-money {
  position: relative;
  left: 45px;
  top: -8px;
}

.box-text {
  position: relative;
  top: -110px;
  left: 20px;
}
.csgo-box {
  color: #fff;
  font-size: 18px;
  font-weight: 900;
}
.csgo-box-money {
  color: #485970;
  font-size: 14px;
}
.middle {
  display: flex;
  padding-top: 50px;
  /* margin-bottom: 50px; */
}
.csgo-middle {
  position: absolute;
  top: 150px;
}

/* 左侧 */
.csgo-left {
  width: 100px;
  height: 100%;
  display: flex;
  justify-content: center;
}
.left {
  width: 50px;
  height: 600px;
  background-color: #111419;
  border-radius: 10px;
  position: fixed;
  top: 100px;
}
.left-svg img {
  width: 32px;
  margin-left: 10px;
  margin-top: 50px;
}
</style>