<template>
  <h1>Привет !</h1>
  <br>
  <div class="descript">
    Доброе пожаловать на N тренировочный день,
    <br>
    Ваш последний результат - решено N из K задач.
    <br>
    Общая точность N%.
  </div>
  <br>
  <h2>Настройки</h2>
  <br>
  <div class="main_game_settings">
    Прописать логику с ползунками
  </div>
  <br>
  <div class="all_formulas_parmas">
    Прописать логику для  v:for
  </div>
  <RouterLink to="/game">
    <button class="play_button">Play !</button>
  </RouterLink>
</template>

<script setup>
import { RouterLink, } from 'vue-router'

</script>

<style>
@media (min-width: 1024px) {
  .descript {
    /*min-height: 100vh;*/
    display: flex;
    align-items: center;
    padding-bottom: 50px;
    padding-top: 5px;
  }
}
</style>

// import Settings from './views/Settings/Settings.vue'
// import HelloWorld from './components/HelloWorld.vue'
