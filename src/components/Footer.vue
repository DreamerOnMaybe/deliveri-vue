<template>
  <footer class="footer">
    <div class="container">
      <div class="footer-box">
        <router-link to="/" class="footer-logo logo">
          <img src="../assets/img/logo.png" alt="Logo" />
        </router-link>
        <div class="footer-nav">
          <ul>
            <li><router-link to="/">Ресторанам</router-link></li>
            <li><router-link to="/">Курьерам</router-link></li>
            <li><router-link to="/">Пресс-центр</router-link></li>
            <li><router-link to="/">Контакты</router-link></li>
          </ul>
        </div>
        <div class="footer-social">
          <img src="../assets/img/socials/inst.png" alt="Inst" />
          <img src="../assets/img/socials/fb.png" alt="FB" />
          <img src="../assets/img/socials/vk.png" alt="VK" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  display: flex;
  align-items: center;
  min-height: 156px;
  padding: 60px 0;
}

.footer-box {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 36px;
  flex-wrap: wrap;
}

.footer-nav {
  flex-grow: 1;
}

.footer-nav ul {
  display: flex;
  align-items: center;
  list-style: none;
  padding: 0;
  margin: 0;
  gap: 15px;
  flex-wrap: wrap;
}

.footer-nav ul li {
  color: #595959;
  font-size: 18px;
  font-weight: 400;
}

.footer-social {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  gap: 20px;
}
</style>