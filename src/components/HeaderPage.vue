<template>
  <div id="app" class="header">
    <img alt="Vue logo" src="img/dc-logo.png">
    <nav>
      <ul>
        <li>CARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBILES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style scoped lang="scss">
 .header {
  display: flex;
  justify-content: space-around;
 }
 ul {
  display: flex;
  justify-content: space-around;
 }
 li {
  list-style: none;
  padding: 5px;
 }
</style>
