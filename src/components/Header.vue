<template>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <div class="header__logo">
          <img src="logo.ico" alt="" />
        </div>
        <nav class="header__nav nav">
          <ul class="nav__list">
            <li class="nav__li"><a href="#technologies">Технологии</a></li>
            <li class="nav__li"><a href="#libraries">Библиотеки</a></li>
            <li class="nav__li"><a href="#frameworks">Фреймворк</a></li>
          </ul>
          <button class="change-color">Сменить тему</button>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.header__inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header__nav {
  display: flex;
  align-items: center;
}
.nav__list {
  display: flex;
  font-size: 1.5rem;
  padding-right: 1rem;
}
.nav__li:not(:first-of-type) {
  padding-left: 1rem;
}
</style>
