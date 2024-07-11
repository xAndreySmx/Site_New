<!-- Здесь перечислены, чем можно заниматься -->
<template>
  <div>
    <div class="flex_container">
      <div class="box">
        <img
          src="..\assets\upload-95d55fa8-fa88-45f1-9a33-b910f19a7c8e.png"
          alt="1"
        />
        <div
          class="text_function"
          @mouseenter="funk_A_1"
          @mouseleave="funk_B_1"
        >
          <div class="text_1 just_text" id="p1">
            Экстремальный джип-тур «Алтай»
          </div>
          <div class="text_2 just_text" id="p2">
            от 3 000 Р / 2 часа маршруты любой сложности услуги гида включены
          </div>
        </div>
      </div>
      <div class="box">
        <img
          src="..\assets\upload-7d014e70-103b-4df5-be68-a258866526f4.jpg"
          alt="1"
        />
        <div
          class="text_function"
          @mouseenter="funk_A_2"
          @mouseleave="funk_B_2"
        >
          <div class="text_1 just_text" id="p3">
            Сплав группами по реке Катунь
          </div>
          <div class="text_2 just_text" id="p4">
            от 1 500 Р/ 2 часа для взрослых и детей маршруты для любого уровня
            физической подготовки
          </div>
        </div>
      </div>
    </div>
    <div class="flex_container">
      <div class="box">
        <img
          src="..\assets\upload-6080d2f0-526b-4aa5-9bfc-fbde769a7718.jpg"
          alt="1"
        />
        <div
          class="text_function"
          @mouseenter="funk_A_3"
          @mouseleave="funk_B_3"
        >
          <div class="text_1 just_text" id="p5">
            Конные прогулки по маршрутам Алтая
          </div>
          <div class="text_2 just_text" id="p6">
            от 700 Р / час для взрослых и детей на выбор несколько маршрутов
          </div>
        </div>
      </div>
      <div class="box">
        <img
          src="..\assets\upload-addd6c2b-05e0-4e73-9a33-0835be57df4a.png"
          alt="1"
        />
        <div
          class="text_function"
          @mouseenter="funk_A_4"
          @mouseleave="funk_B_4"
        >
          <div class="text_1 just_text" id="p7">
            Экскурсии по заповедным местам
          </div>
          <div class="text_2 just_text" id="p8">
            на выбор более 10 экскурсий по уникальным местам Алтая
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "activitiesItem",
  methods: {
    function_A_1() {
      document.getElementById("p1").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_A_2() {
      document.getElementById("p1").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_1() {
      document.getElementById("p2").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_2() {
      document.getElementById("p2").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    funk_A_1() {
      this.function_A_1();
      this.function_B_1();
    },
    funk_B_1() {
      this.function_A_2();
      this.function_B_2();
    },
    /////////////////////////////////////////
    /////////////////////////////////////////
    function_A_3() {
      document.getElementById("p3").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_A_4() {
      document.getElementById("p3").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_3() {
      document.getElementById("p4").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_4() {
      document.getElementById("p4").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    funk_A_2() {
      this.function_A_3();
      this.function_B_3();
    },
    funk_B_2() {
      this.function_A_4();
      this.function_B_4();
    },
    ////////////////////////
    ////////////////////////
    function_A_5() {
      document.getElementById("p5").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_A_6() {
      document.getElementById("p5").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_5() {
      document.getElementById("p6").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_6() {
      document.getElementById("p6").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    funk_A_3() {
      this.function_A_5();
      this.function_B_5();
    },
    funk_B_3() {
      this.function_A_6();
      this.function_B_6();
    },
    ///////////////////////////
    ////////////////////////
    function_A_7() {
      document.getElementById("p7").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_A_8() {
      document.getElementById("p7").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_7() {
      document.getElementById("p8").animate([{ opacity: 0 }, { opacity: 1 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    function_B_8() {
      document.getElementById("p8").animate([{ opacity: 1 }, { opacity: 0 }], {
        duration: 300,
        delay: 300,
        fill: "forwards",
      });
    },
    funk_A_4() {
      this.function_A_7();
      this.function_B_7();
    },
    funk_B_4() {
      this.function_A_8();
      this.function_B_8();
    },
  },
};
</script>
<style scoped>
.flex_container {
  display: flex;
  place-content: center;
  justify-content: space-evenly;
  gap: 5%;
}
.box {
  width: 40%;
  min-width: 30%;
  margin-top: 3%;
  border-radius: 20px;
  background-color: rgb(230, 219, 219);
}
.text_function {
  color: rgb(141, 120, 82);
  position: relative;
  text-align: center;
  width: 100%;
  height: 100%;
}
img {
  position: relative;
  float: left;
  width: 28%;
  border-radius: 20px;
  margin: 1%;
  margin-left: 1%;
}

.text_1 {
  position: absolute;
  font-size: 2vw;
  margin-left: 30%;
  padding: 1%;
  top: 25%;
}
.text_2 {
  font-size: 1.5vw;
  position: absolute;
  opacity: 0;
  margin-left: 30%;
  padding: 1%;
  top: 25%;
  /* это нужно, чтобы второй текст был прозрачным и стоял за первым */
}
</style>
