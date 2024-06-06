<template>
  <div class="topMenu">
    <div class="topMenuL">
      <img class="logo" src="/picture/logo.png" alt="logo" />
      <p>THỰC ĐƠN</p>
      <p>KHUYẾN MÃI</p>
      <p>DỊCH VỤ TIỆC</p>
      <p>HỆ THỐNG NHÀ HÀNG</p>
    </div>
    <div class="topMenuR">
      <input class="btnBooking"  type="button" value="     Bắt đầu đặt hàng     ">
      <p>English</p>
      <img class="iconMem" src="/picture/iconMember.jpg" alt="">
      <img class="iconMem" src="/picture/iconShopping.jpg" alt="">
      <img class="iconMem" src="/picture/iconMenu.jpg" alt="">
    </div>
  </div>
</template>

<style scoped>
.iconMem{
  height: 42px;
}
.topMenu {
  width: 100%;
  padding-left: 5%;
  padding-right: 5%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content:space-around;
}
.logo {
  height: 78px;
  width: 78px;
}
.topMenuL {

  
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 17px;
  font-weight: 700;
  flex-direction: row;
  gap: 40px;
}
.topMenuR{
   
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 17px;
    font-weight: 700;
    flex-direction: row;
    margin-right: 40px ;
    gap: 40px;
}
.btnBooking{
    height: 35px;
    width: 200px;
    border-radius: 20px;
    background-color: #f13d3d;
    color: azure;
    font-weight: 700;
    border: none;
    margin-right: 5px;
}
p {
  text-decoration: none;
  transition: text-decoration 0.3s ease;
}

p:hover {
  text-decoration: underline;
}
</style>

<script setup>

</script>
