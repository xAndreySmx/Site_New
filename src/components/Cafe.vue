<!--Кафе -->
<template>
  <div>
    <div class="main_container">
      <h2 class="just_text main_text">Уютное кафе с демократичными ценами</h2>
      <div class="flex_container">
        <div class="left just_text">
          <!-- левая часть  -->
          <p>
            Чтобы насладиться завтраком обедом или ужином не нужно покидать
            территорию базы отдыха достаточно перейти в домик по соседству
          </p>
          <br />
          <p>Часы работы 9:00 до 21:00</p>
          <button class="menu_button"><a href=""></a>Меню</button>
          <!--тут должна быть ссылка на меню-->
          <div class="img_flex_container">
            <div class="image">
              <img
                src="..\assets\upload-711e4955-7a6b-43a8-ab3b-13089d47a28f.jpg"
                alt="1"
              />
            </div>
            <div class="image">
              <img
                src="..\assets\upload-4577f4bd-8aed-433b-94a7-35e386e36e37.jpg"
                alt="2"
              />
            </div>
            <div class="image">
              <img
                src="..\assets\upload-f126cca4-3da0-48e2-bcce-67192804aa8f.jpg"
                alt="3"
              />
            </div>
          </div>
        </div>
        <div class="right just_text">
          <ul>
            <li>настольные игры</li>
            <li>спортивный бар</li>
            <li>организация банкетов</li>
            <li>спутниковое ТВ</li>
            <li>небольшая библиотека</li>
            <li>караоке</li>
            <li>WI-FI</li>
          </ul>
        </div>
        <!-- правая часть -->
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "CafeItem",
};
</script>
<style scoped>
.menu_button {
  display: block;
  transition-property: background-color, color;
  transition-duration: 0.4s;
  transition-timing-function: ease-out;
  background-color: rgb(245, 247, 242);
  width: 12vw;
  height: 4.5vh;
  border-radius: 14px;
  border-width: 1px;
  border-color: rgb(41, 67, 50);
  box-shadow: 1px 1px 1px black;
  font-family: Roboto;
  font-style: normal;
  color: rgb(41, 67, 50);
  font-size: 1.8vw;
  letter-spacing: 0px;
}
.menu_button:hover {
  background-color: rgb(41, 67, 50);
  border-radius: 14px;
  border-width: 1px;
  border-color: rgb(41, 67, 50);
  font-family: Roboto;
  font-weight: 400;
  font-style: normal;
  color: rgb(245, 247, 242);
  font-size: 1.8vw;
  letter-spacing: 0px;
  cursor: pointer;
}
.main_container {
  padding-top: 2%;
  background-color: rgb(242, 230, 215);
}
.flex_container {
  display: flex;
  place-content: center;
  justify-content: space-evenly;
}
.img_flex_container {
  display: flex;
  place-content: center;
  justify-content: space-evenly;
  margin-right: 1%;
}
.image {
  width: 15vw;
  margin-top: 2%;
  margin-bottom: 2%;
}
img {
  height: 100%;
  width: 100%;
  border-radius: 20px;
}
.just_text {
  color: rgb(141, 120, 82);
  font-size: 2vw;
}
.main_text {
  font-size: 2.5vw;
}
.right {
  border-left: 2px solid;
  padding-left: 5%;
  padding-right: 10%;
  letter-spacing: 1px;
}
li {
  margin-top: 12%; /* нужно для отступов между строками в правой таблице */
}
</style>
