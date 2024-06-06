<template>
    <div>
        <p>DANH MỤC MÓN ĂN</p>
    </div>
    <div class="menu">
        <div class="grid-container">
            <div class="product" v-for="(food, index) in foods" :key="index">
                <img :src="food.src">
                <input class="btn" type="button"  :id="food.id" :value="food.btn">

             </div>            
          </div>
    </div>
    <!-- <img src="/picture/COMBO1NGUOI.jpg" alt=""> -->
</template>

<style scoped>
.grid-container {
   max-width: 100%;
    display:flex;
    overflow: auto;
    margin: 10px;
    gap: 40px;
    justify-content: center;
  }
  .grid-item {
    background-color: rgba(255, 255, 255, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 20px;
    font-size: 30px;
    text-align: center;
  }
  .product{
    width: 30%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;

}
.menu{
    width: 100%;
    display: flex;
    justify-content: center;
}
.btn{
    background-color: white;
    height: 50px;
    text-align: left;
    font-size: larger;
    font-weight: 700;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    border: none;
    border-bottom-right-radius: 6px;
    border-bottom-left-radius: 6px;

}
.btn:hover{
    border: solid 1px gray;
}
</style>

<script setup>
             const   foods= [
                    { id: 'Product1', btn: "ƯU ĐÃI", currency: 'USD' , src:'./picture/khuyenMai.jpg'},
                    { id: 'Product2', btn: "MÓN  MỚI", currency: 'USD', src:'./picture/monMoi.jpg' },
                    { id: 'Product3', btn: "Combo 1 người", currency: 'USD',src:'./picture/COMBO1NGUOI.jpg' },
                    { id: 'Product4', btn: "Combo nhóm", currency: 'USD',src:'./picture/COMBONHOM.jpg' }
             ]
</script>