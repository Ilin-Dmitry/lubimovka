<template>
  <div class="project">
    <p class="project__title project__title_l">После ознакомления со стилями код внутри .project можно удалить</p>
    <p class="project__title project__title_l">С_училища</p>
    <p class="project__title project__title_s">
      Пьеса о демоническом обаянии студентки ПТУ и ее роковой роли в жизни
      преподавателя философии.
    </p>
    <p class="project__title project__title_m">12 мая 20:00</p>
    <p class="project__title project__title_m">Почитать пьесу</p>
    <p class="project__text project__text_xl">
      Пьеса «Длань Господня» (Hand to God) — лауреат американской театральной
      премии OBIE (Off-Broadway Theater Awards), номинант ежегодно присуждаемой
      премии TONY (Theatre Of New York), театрального аналога «Оскара», и
      номинант на Британскую премию Лоуренса Оливье в качестве «Лучшей Новой
      Комедии». Она была поставлена в бродвейских театрах и в лондонском
      Вест-Энде.
    </p>
    <p class="project__text project__text_l">Сборник Любимовка.Пьесы</p>
    <p class="project__text project__text_m">Драматург</p>
    <p class="project__text project__text_xl">Роберт Аскинс</p>
    <p class="project__text project__text_s">
      вёрстка и разработака — студенты Яндекс.Практикума
    </p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
  components: {},
});
</script>

<style lang="scss">
@font-face {
  font-family: "Formular Lifght";
  src: local("Formular Light"),
    url(./assets/fonts/formular-light.woff2) format("woff2"),
    url(./assets/fonts/formular-light.woff) format("woff"),
    url(./assets/fonts/formular-light.eot) format(e "mbedded-opentype");
  font-weight: 300;
  font-style: normal;
}
@font-face {
  font-family: "Neue Machina";
  src: local("Neue Machina"),
    url(./assets/fonts/NeueMachina-Regular.woff2) format("woff2"),
    url(./assets/fonts/NeueMachina-Regular.woff) format("woff"),
    url(./assets/fonts/NeueMachina-Regular.eot) format("embedded-opentype"),
    url(./assets/fonts/NeueMachina-Regular.ttf) format("truetype"),
    url(./assets/fonts/NeueMachina-Regular.otf) format("opentype");
  font-weight: 400;
  font-style: normal;
}


.project {
  color: #242424;
  &__title {
  font-family: "Neue Machina", courier, monospace;
  font-weight: 400;
  letter-spacing: -1px;
  &_l {
    font-size: 40px;
    line-height: 1;
  }
  &_m {
    font-size: 28px;
    line-height: calc(32 / 28);
  }
  &_s {
    font-size: 20px;
    line-height: calc(24 / 20);
  }
}
&__text {
  font-family: "Formular Light", Arial, Helvetica, sans-serif;
  font-weight: 300;
  letter-spacing: 0px;
  &_xl {
    font-size: 20px;
    letter-spacing: -1px;
    line-height: calc(28 / 20);
  }
  &_l {
    font-size: 18px;
    line-height: calc(23 / 18);
  }
  &_m {
    font-size: 16px;
    line-height: calc(22 / 16);
  }
  &_s {
    font-size: 14px;
    line-height: calc(17 / 14);
  }
}
}
</style>
