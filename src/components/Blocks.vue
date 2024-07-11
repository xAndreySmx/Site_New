<!-- Блок с картинками -->
<template>
  <div>
    <div class="block">
      <div class="flex_text_container">
        <div class="text text_container_1">
          АлтайРай - это место, где вам будет хорошо
        </div>
        <div class="text text_container_2">
          База отдыха расположена в живописном месте Горного Алтая на территории
          РК «Рублёвка» с собственным пляжем, аквапарком и множеством активных
          развлечений
        </div>
      </div>
      <div class="flex_container">
        <figure class="box_text">
          <img
            src="../assets/upload-1fcfc97d-cbce-4419-9017-090c4dcae143.png"
            class="small_images"
            alt="два бассейна"
          />
          <figcaption>два бассейна с подогревом</figcaption>
        </figure>
        <figure class="box_text">
          <img
            src="../assets/upload-15f1ffc3-979f-4d96-92e0-051cea10a5d5.png"
            class="small_images"
            alt="кафе"
          />
          <figcaption>кафе</figcaption>
        </figure>
        <figure class="box_text">
          <img
            src="../assets/upload-02647ffa-b991-4b60-8c60-6a2b375e1de5.png"
            class="small_images"
            alt="батут"
          />
          <figcaption>детский батут</figcaption>
        </figure>
        <figure class="box_text">
          <img
            src="../assets/upload-f62da51a-d36d-4fe6-918f-eb59413035d0.png"
            class="small_images"
            alt="площадка"
          />
          <figcaption>детская площадка</figcaption>
        </figure>
      </div>
      <div class="flex_container">
        <figure class="box_text">
          <img
            src="../assets/upload-aed17484-5a15-43e6-bbd9-0abdf68f6fc0.png"
            class="small_images"
            alt="игры"
          />
          <figcaption>настольные игры для всей семьи</figcaption>
        </figure>
        <figure class="box_text">
          <img
            src="../assets/upload-41b35ac7-35fd-4c3c-ba9f-b0e30c6e6439.png"
            class="small_images"
            alt="баня"
          />
          <figcaption>баня</figcaption>
        </figure>
        <figure class="box_text">
          <img
            src="../assets/upload-d95de2fe-ae19-46e4-8034-211e11611613.png"
            class="small_images"
            alt="автостоянка"
          />
          <figcaption>автостоянка</figcaption>
        </figure>
        <figure class="box_text">
          <img
            src="../assets/upload-73582da6-2297-4c11-a69b-fea03edcf3a1.png"
            class="small_images"
            alt="беседки"
          />
          <figcaption>беседка с мангалами</figcaption>
        </figure>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "BlockS",
};
</script>
<style scoped>
.block {
  background-color: rgb(242, 230, 215);
  color: rgb(141, 120, 82);
  padding-top: 60px;
  padding-bottom: 40px;
  border-bottom-left-radius: 35px;
  border-bottom-right-radius: 35px;
}
.flex_container {
  display: flex;
  place-content: center;
  justify-content: space-evenly;
  /* background-color: rgb(242, 230, 215);
  color: rgb(141, 120, 82); */
}
.flex_text_container {
  display: flex;
  height: 60vh;
  place-content: center;
  justify-content: space-evenly;
  gap: 10%;
}
.text_container_1 {
  width: 40%;
  font-size: 4vw;
  font-weight: bolder;
  align-content: center;
  letter-spacing: 5px;
}
.text_container_2 {
  width: 40%;
  align-content: center;
  font-size: 2.5vw;
}
.box_text {
  flex-basis: 14em;
  font-size: 20px;
  text-align: center;
}
.small_images {
  width: 100%;
  min-width: 100px;
}
</style>
