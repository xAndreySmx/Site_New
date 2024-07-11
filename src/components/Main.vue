<template>
  <div class="body">
    <div id="top" class="header_item">
      <img class="header_image" src="..\assets\mountains.jpg" alt="" />
      <div class="anchors">
        <a href="#contacts" class="menuButton button" v-smooth-scroll>
          Контакты</a
        >
        <a href="#reviews" class="menuButton button" v-smooth-scroll> Отзывы</a>
        <a href="#activities" class="menuButton button" v-smooth-scroll>
          Развлечения</a
        >
        <a href="#cafe" class="menuButton button" v-smooth-scroll> Кафе</a>
        <a href="#houses" class="menuButton button" v-smooth-scroll
          >Категории домов</a
        >
      </div>
      <h1 class="header_main">Алтай Рай</h1>
      <h2 class="header">Семейная база отдыха в горах Алтая</h2>
      <p class="text">
        Это прекрасная возможность расслабиться телом и душой, живописные горные
        пейзажи, уникальная природа, чистый воздух делают это место незабываемым
        и идеальным для семейного отдыха
      </p>
      <button class="book_button button">Забронировать</button>
    </div>
    <Blocks />
    <h1 class="categor">Категории домов</h1>
    <div id="houses" class="houses">
      <div>
        <House_1 class="house_1" />
        <House_2 class="house_2" />
        <House_3 class="house_3" />
      </div>
    </div>
    <h1 id="cafe" class="categor">Кафе</h1>
    <Cafe />
    <h1 id="activities" class="categor">Чем заняться</h1>
    <Activities />
    <h1 id="reviews" class="categor">Отзывы</h1>
    <Reviews />
    <h1 id="contacts" class="categor">Контакты</h1>
    <Contacts />
    <a href="#top" class="go-top" v-smooth-scroll> </a>
  </div>
</template>
<script>
import House_1 from "./House_1.vue";
import House_2 from "./House_2 .vue";
import House_3 from "./House_3.vue";
import Activities from "./Activities.vue";
import Blocks from "./Blocks.vue";
import Cafe from "./Cafe.vue";
import Reviews from "./Reviews.vue";
import Contacts from "./Contacts.vue";
// import function to register Swiper custom elements
import { register } from "swiper/element/bundle";
// register Swiper custom elements. Swiper - это плагин для создания слайдов-каруселей из изображений и тд
register();
export default {
  name: "MainC",
  components: {
    House_1,
    House_2,
    House_3,
    Activities,
    Blocks,
    Cafe,
    Reviews,
    Contacts,
  },
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"); /* импорт стилей*/
.body {
  background-color: #0b4122;
  font-family: Roboto;
}
.header_item {
  position: relative;
  width: 100%;
  height: 100vh;
  background-color: black;
}
.header_image {
  position: absolute;
  width: 100%;
  min-width: 900px;
  height: 100%;
  opacity: 70%;
  z-index: 0;
}
.header_main {
  position: relative;
  display: block;
  top: 120px;
  left: 80px;
  width: auto;
  min-width: 300px;
  height: 72px;
  min-height: 72px;
  font-size: 10vh;
  color: white;
}
.header {
  position: relative;
  display: block;
  top: 200px;
  left: 80px;
  width: 900px;
  font-size: 7vh;
  color: white;
}
.anchors {
  position: absolute;
  right: 0;
}
.menuButton {
  position: relative;
  transition-property: background-color, color;
  transition-duration: 0.4s;
  transition-timing-function: ease-out;
  right: 7px;
  top: 5px;
  margin-right: 2px;
  padding: 4px;
  text-align: center;
  color: white;
  font-family: Roboto;
  font-weight: bolder;
  font-size: 20px;
  text-decoration: none;
}
.menuButton:hover {
  position: relative;
  color: rgb(0, 126, 17);
}
.text {
  position: relative;
  display: block;
  top: 200px;
  left: 80px;
  width: 900px;
  font-size: 30px;
  font-weight: 300;
  color: white;
}
.book_button {
  position: relative;
  top: 200px;
  left: 80px;
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
  font-size: 30px;
  padding: 12px;
  padding-left: 30px;
  padding-right: 30px;
}
.book_button:hover {
  background-color: rgb(41, 67, 50);
  border-color: rgb(41, 67, 50);
  font-weight: 400;
  font-style: normal;
  color: rgb(245, 247, 242);
  cursor: pointer;
}
.houses {
  background-color: rgb(242, 230, 215);
}
.categor {
  color: white;
  text-align: center;
}
.go-top {
  /* display: none; */
  position: fixed;
  width: 30px;
  height: 30px;
  left: 97%;
  top: 90%;
  border-radius: 50%;
  opacity: 70%;
  background-color: rgb(239, 94, 61);
}
.go-top:hover {
  background-color: rgb(66, 182, 113);
}
</style>
