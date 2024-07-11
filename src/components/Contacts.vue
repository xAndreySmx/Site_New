<template>
  <div class="container">
    <div class="contacts">
      <p>+7 (963) 537-99-96</p>
      <p>altairai@yandex.ru</p>
      <p>
        Республика Алтай, Чемальский район, территория РК «Рублевка», между
        селами Анос и Аюла
      </p>
      <p>Широта 51°28′37″N (51.476913) Долгота 85°58′35″E (85.976466)</p>
      <a href="">"Ссылка на Vk, telegram или другое"</a>
    </div>
    <div class="mapItem">
      <iframe
        src="https://yandex.ru/map-widget/v1/?from=mapframe&ll=85.978103%2C51.449633&mode=usermaps&source=mapframe&um=constructor%3Ae5315970d6f59b08a1ff6c810a3c206da91fd85e317233ee079d36dbd7e054b1&utm_source=mapframe&z=10"
        width="540px"
        height="400px"
        position="relative"
        right="500px"
        frameborcontainer="1"
        allowfullscreen="true"
      ></iframe>
    </div>
  </div>
</template>
<script>
export default {
  name: "contactsS",
};
</script>
<style scoped>
.container {
  display: flex;
  justify-content: space-around;
}
.mapItem {
  height: auto;
  width: auto;
  position: relative;
  margin-right: 7%;
}
.contacts {
  color: rgba(255, 255, 255, 1);
  font-size: 20px;
}
a {
  color: white;
}
a:hover {
  color: rgb(18, 160, 0);
}
</style>
