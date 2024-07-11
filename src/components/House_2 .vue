<!-- Здесь написано все про дома и условия -->
<template>
  <div class="div_container">
    <p class="house_name">ПОЛУЛЮКС</p>
    <swiper-container
      class="mySwiper"
      pagination="true"
      navigation="true"
      space-between="30"
      loop="true"
    >
      <swiper-slide
        ><img src="..\assets\upload-3f871443-5b0b-4ea0-b2c8-ad876da12994.jpg" />
      </swiper-slide>
      <swiper-slide
        ><img src="..\assets\upload-0a963bd8-6e33-407b-894c-9dad129d903f.jpg"
      /></swiper-slide>
      <swiper-slide
        ><img src="..\assets\upload-43754e98-c1bf-4659-82ee-ba760c11be99.jpg"
      /></swiper-slide>
    </swiper-container>
    <button class="price_button">От 7900 Р/ сутки</button>
    <ul class="list_border">
      <li>24 м² (4 спальных места)</li>
      <li>две комнаты</li>
      <li>санузел с душевой кабиной</li>
      <li>терасса с гамаком</li>
      <li>отдельный вход</li>
      <li>чайник, посуда, и столовые приборы</li>
      <li>ТВ</li>
      <li>Гигиенические наборы</li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "house-item-2",
  data() {
    return {
      // image: require("../assets/logo.png"),
    };
  },
};
</script>
<style scoped>
.div_container {
  display: inline-block;
  width: 28%;
  height: 45vh;
  min-width: 20%;
  min-height: 20%;
  margin-right: 5%;
}
swiper-container {
  width: 100%;
  height: 100%;
}

swiper-slide {
  text-align: center;
  font-size: 18px;

  display: flex;
  justify-content: center;
  align-items: center;
}

swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 30px;
}

swiper-container {
  margin-left: auto;
  margin-right: auto;
}
.house_name {
  text-align: center;
  font-size: 2vw;
  font-weight: bold;
  color: rgb(141, 120, 82);
  letter-spacing: 1px;
}
.list_border {
  margin-top: 10%;
  border-left: 2px solid;
  border-right: 2px solid;
  color: rgb(141, 120, 82);
  font-size: 1.6vw;
}
.price_button {
  display: block;
  transition-property: background-color, color;
  transition-duration: 0.4s;
  transition-timing-function: ease-out;
  background-color: rgb(245, 247, 242);
  border-radius: 14px;
  border-width: 1px;
  border-color: rgb(41, 67, 50);
  box-shadow: 1px 1px 1px black;
  font-family: Roboto;
  font-style: normal;
  color: rgb(41, 67, 50);
  font-size: 2vw;
  margin-top: 5%;
}
.price_button:hover {
  background-color: rgb(41, 67, 50);
  border-radius: 14px;
  border-width: 1px;
  border-color: rgb(41, 67, 50);
  font-family: Roboto;
  font-weight: 400;
  font-style: normal;
  color: rgb(245, 247, 242);

  cursor: pointer;
}
</style>
