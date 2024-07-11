<template>
  <div>
    <div class="container">
      <div class="rev_item">
        <p>Дмитрий</p>
        <p>
          Замечательное и красивое место! Домики неплохие! Баня хорошая!
          Гостеприимный персонал, умеют находить общий язык с посетителями.
          Будет возможность вернёмся ещё!))
        </p>
      </div>
      <div class="rev_item">
        <p>Алена</p>
        <p>
          Прекрасное место! Добрые и отзывчивые девочки тут работают) Чистая
          территория с великолепными видами, хорошие домики! Хочется вернуться
          туда!
        </p>
      </div>
      <div class="rev_item">
        <p>Юля</p>
        <p>
          Супер место, очень дружелюбные сотрудники, всегда во всем помогут
          иподскажут, домики удобные, все есть, классная территория,
          обустроенная для всего, шикарные виды
        </p>
      </div>
      <div class="rev_item">
        <p>Егор</p>
        <p>
          Это отличная база, в тихом и живописном месте рядом с трассой. Езжу
          сюда, уже несколько лет. Очень удобные и просторные домики с террасой
          и гамаком. Отдельное спасибо хозяевам!! Желаю вам процветания!
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "RewItem",
};
</script>
<style scoped>
.container {
  display: flex;
  place-content: center;
  justify-content: space-evenly;
}
.rev_item {
  font-size: 2vw;
  background-color: rgb(202, 186, 186);
  color: rgb(141, 120, 82);
  border: 2px solid;
  border-radius: 20px;
  margin: 10px;
  padding: 10px;
  text-align: center;
}
</style>
