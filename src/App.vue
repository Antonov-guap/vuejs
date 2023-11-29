<script setup>

</script>

<template>
  <nav>
    <span><b>Sandbox</b></span><span>Сборки</span><span>Создать сборку</span>
    <span>Приложения</span><span>Шаблоны</span><span>Агрегаты</span>
  </nav>
  <main>

  </main>
</template>

<style lang="scss">
$navColor: #eee;
$navBackColor: #37474F;
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Verdana, sans-serif;
  font-size: 0.75em;
}

nav {
  background-color: $navBackColor;
  color: $navColor;

  span {
    padding: 1.3em 1.3em;
    display: inline-block;
    cursor: pointer;

    &:hover {
      background-color: lighten($navBackColor, 20%);
      color: lighten($navColor, 20%);
    }
  }
}
</style>

