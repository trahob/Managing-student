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
      <img height="42px" src="/picture/iconMember.jpg" alt="">
      <img height="42px" src="/picture/iconShopping.jpg" alt="">
      <img height="37px" src="/picture/iconMenu.jpg" alt="">
    </div>
  </div>
</template>

<style scoped>
.topMenu {
    padding-left: 5%;
    padding-right: 5%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}
.logo {
  height: 78px;
  width: 78px;
}
.topMenuL {

  width: 55%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-size: 17px;
  font-weight: 700;
  flex-direction: row;
}
.topMenuR{
    width: 25%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 17px;
    font-weight: 700;
    flex-direction: row;
    margin-right: 40px ;
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
</style>

<script setup></script>
