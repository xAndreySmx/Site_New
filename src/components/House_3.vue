<!-- Здесь написано все про дома и условия -->
<template>
  <div class="div_container">
    <p class="house_name">ЛЮКС</p>
    <swiper-container
      class="mySwiper"
      pagination="true"
      navigation="true"
      space-between="30"
      loop="true"
    >
      <swiper-slide
        ><img src="..\assets\upload-c4d2e6af-f6e6-4f43-afb3-7a371d647157.jpg" />
      </swiper-slide>
      <swiper-slide
        ><img src="..\assets\upload-fb81c451-279e-4c63-8cc9-e9be5a47b4d7.jpg"
      /></swiper-slide>
      <swiper-slide
        ><img src="..\assets\upload-bbe1677f-742d-4268-9e5e-18f670e5b333.jpg"
      /></swiper-slide>
    </swiper-container>
    <button class="price_button">От 9900 Р/ сутки</button>
    <ul class="list_border">
      <li>24 м² (4 спальных места)</li>
      <li>две комнаты</li>
      <li>санузел с душевой кабиной</li>
      <li>терасса с гамаком</li>
      <li>отдельный вход</li>
      <li>чайник, посуда, и столовые приборы</li>
      <li>ТВ + Гигиенические наборы + фен</li>
    </ul>
  </div>
  <p class="just_text">Дополнительное место оплачивается отдельно:</p>
  <p class="just_text">Взрослое – 1000 Р</p>
  <p class="houses_bottom_line just_text">Детское – 500 Р</p>
  <div class="flex_container">
    <figure class="box">
      <img
        src="..\assets\upload-f1eb1f18-9424-4cc4-87f3-b934389a92e5.png"
        class="small_images"
        alt="1"
      />
      <figcaption>Завтрак включен в стоимость</figcaption>
    </figure>
    <figure class="box">
      <img
        src="..\assets\upload-dbf16add-7a3f-415b-b521-22a9bb44c1dc.png"
        class="small_images"
        alt="2"
      />
      <figcaption>Можно с животными</figcaption>
    </figure>
    <figure class="box">
      <img
        src="..\assets\upload-586c4f8a-57a4-458a-b9f2-1ffe262e95e0.png"
        class="small_images"
        alt="3"
      />
      <figcaption>Дети до 5 лет бесплатно</figcaption>
    </figure>
    <figure class="box">
      <img
        src="..\assets\upload-15ebcb37-4465-4097-b43c-d499f43048d1.png"
        class="small_images"
        alt="4"
      />
      <figcaption>WI - FI</figcaption>
    </figure>
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
.flex_container {
  display: flex;
  place-content: center;
  justify-content: space-evenly;
  background-color: rgb(242, 230, 215);
  color: rgb(141, 120, 82);
}
.small_images {
  width: 30%;
  height: 50%;
  min-width: 20%;
  min-height: 20%;
}
.just_text {
  color: rgb(141, 120, 82);
  font-size: 14px;
}
figcaption {
  font-size: 13px;
}
</style>
