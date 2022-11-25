<template>
  <div class="contenitore-header">
    <div class="header">
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
    <div class="contenitore-2">
      <h1 class="black"> Content goes here </h1>
    </div>
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
  padding: 20px;
 }
 .black {
  padding: 30px;
  color: white;
  margin-left: 100px;
 }
 .contenitore-2 {
  background-color: black;
 }
</style>
