<template>
  <body>
  <div class="grid-container">
    <a href="https://store.steampowered.com/" target="_blank">
      <img src="https://www.pngmart.com/files/22/Steam-Logo-PNG.png" style="width: 10%; height: 50%;" alt="pic">
    </a>
    <a href="https://store.steampowered.com/" class="button-link">商店</a>
    <a href="https://steamcommunity.com/" class="button-link">社群</a>
    <a href="https://store.steampowered.com/about/" class="button-link">關於</a>
    <a href="https://help.steampowered.com/zh-tw/" class="button-link">客服中心</a>
  </div>
  <div class="funfun">
    <a href="https://store.steampowered.com/about/" class="funb1">安裝 Steam</a>
    <a href="" class="funb">登入</a>
    <a href="" class="funb">語言</a>
  </div>
  <h1>Steam 登錄</h1>
  <div class="login-box">
    <form>
      <label for="username">用戶名 Username</label>
      <input type="text" id="username" name="username" required>
      <label for="password">密碼 Password</label>
      <input type="password" id="password" name="password" required>
      <button onclick="alert('賬號bang不見')" type="submit">登錄 Login</button>
      <a href="https://help.steampowered.com/zh-tw/wizard/HelpWithLogin?redir=https%3A%2F%2Fstore.steampowered.com%2Flogin%2F%3Fredir%3Dabout%252F%26redir_ssl%3D1%26snr%3D1_14_4__global-header" class="forget">忘記密碼?</a>
    </form>
  </div>

  </body>
</template>

<script>
export default {
  name: "steam"
}
</script>

<style scoped>
body {
  background-color: #171a21;
  color: #fff;
  font-family: Arial, sans-serif;
  font-size: 16px;
}

.button-link {
  color: gainsboro;
  text-decoration: none;
  font-size: 16px;
  padding: 30px;
  transition: background-color 0.3s;
}

.button-link:hover {
  color: white
}

.funb1 {
  color: gainsboro;
  text-decoration: none;
  font-size: 10px;
  padding: 30px;
  width: 80px;
  height: 0px;
  transition: background-color 0.3s;
  background-color: #4CAF50;
}

.funb1:hover {
  color: white
}

.forget {
  color: gray
}

.forget:hover {
  color: white
}

.funb {
  color: gainsboro;
  text-decoration: none;
  font-size: 10px;
  width: 40px;
  padding: 30px;
  transition: background-color 0.3s;
}

.funb:hover {
  color: white
}

img[alt="pic"] {
  min-width: 200px;
  min-height: 60px;
}

.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto auto;
  padding: 10px;
  margin-top: 3%;
  margin-left: 15%;
  max-width: 600px;
}

.funfun {
  display: flex;
  min-width: 30px;
  position: absolute;
  top: 0;
  right: 10%;
}

.login-box {
  width: 400px;
  margin: auto;
  padding: 40px;
  background-color: #1b2838;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

h1 {
  text-align: center;
  margin-bottom: 40px;
}

label {
  display: block;
  margin-bottom: 10px;
}

input[type="text"],
input[type="password"] {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border-radius: 5px;
  border: none;
  background-color: #e1e1e1;
  color: #000;
  font-size: 16px;
  font-family: Arial, sans-serif;
}

button[type="submit"] {
  display: block;
  width: 100%;
  padding: 10px;
  margin-top: 20px;
  border-radius: 5px;
  border: none;
  background-color: #00adee;
  color: #fff;
  font-size: 16px;
  font-family: Arial, sans-serif;
  cursor: pointer;
}

button[type="submit"]:hover {
  background-color: #0077be;
}
</style>