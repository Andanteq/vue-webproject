<template>
  <div class="header-top">
    <div class="header-top-menu">
      <ul class="header-top-menu_list">
        <li class="header-top-menu_el">Добавить объявление</li>
        <li class="header-top-menu_el">Создать резюме</li>
        <li class="header-top-menu_el">Войти</li>
      </ul>
    </div>
    <h1>ОНЛАЙН <br> БИРЖА ДЛЯ <br> СТУДЕНТОВ</h1>
  </div>
  <div class="selection">
      <div class="selection-text">ПОДБОРКА ВАКАНСИЙ ДЛЯ ВАС</div>
      <div class="selection-blocks">
        <div class="selection-blocks_el">
          <div class="selection-blocks_text">РАЗРАБОТЧИК</div>
        </div>
        <div class="selection-blocks_el">
          <div class="selection-blocks_text">UX/UI ДИЗАЙНЕР</div>
        </div>
        <div class="selection-blocks_el">
          <div class="selection-blocks_text">ПРОГРАММИСТ</div>
        </div>
      </div>
      <div>        
        <img class="left-arrow" src="./arrow_left.png" @click="LeftScroll(selection-blocks_el)">
        <img class="right-arrow" src="./arrow_right.png" @click="RightScroll(selection-blocks_el)">
      </div>
  </div>
  <div class="search">
    <div class="search-text">ПОИСК ВАКАНСИЙ</div>
  </div>
  <!-- <div class="shapka">
    <button class="profile" type="button" @mousedown="methods">
      <img src="./icon.png"/>
    </button>
  </div> -->
</template>

<style scoped src="./style.css"/>

<script setup>
  function LeftScroll(el) {

  }
</script>


