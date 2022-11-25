<template>
  <div class="contenitore-header">
    <div class="header">
      <img alt="Vue logo" class="dc" src="img/dc-logo.png">
      <nav>
        <ul>
          <li v-for="eleMenu in arrMenu" :key="eleMenu.text">
            <a :href="eleMenu.url">{{eleMenu.text}}</a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="contenitore-2">
      <CardPage v-for="objCard in arrCard"
      :key="objCard" class="card-dc"
      imgUrl="objCArd.scr"
      :title="objCard.titolo"/>
    </div>
  </div>
</template>

<script>
import CardPage from './CardsPage.vue';

export default {
  name: 'HeaderPage',
  comments: {
    CardPage,
  },
  data() {
    return {
      arrMenu: [
        {
          url: '#CARACTERS',
          text: 'CARACTERS',
        },
        {
          url: '#COMICS',
          text: 'COMICS',
        },
        {
          url: '#MOVIES',
          text: 'MOVIES',
        },
        {
          url: '#TV',
          text: 'TV',
        },
        {
          url: '#GAMES',
          text: 'GAMES',
        },
        {
          url: '#COLLECTIBLES',
          text: 'COLLECTIBLES',
        },
        {
          url: '#VIDEOS',
          text: 'VIDEOS',
        },
        {
          url: '#FANS',
          text: 'FANS',
        },
        {
          url: '#NEWS',
          text: 'NEWS',
        },
        {
          url: '#SHOP',
          text: 'SHOP',
        },
      ],
      arrCard: [

      ],
    };
  },
};
</script>

<style scoped lang="scss">
 .header {
  display: flex;
  justify-content: space-around;
 }
 .dc {
  padding: 10px;
 }
 ul {
  display: flex;
  justify-content: space-around;
 }
 li {
  list-style: none;
  padding: 20px;
  margin-top: 20px;
  display: flex;
  align-items: center;
 }
 .black {
  padding: 50px;
  color: white;
  margin-left: 100px;
 }
 .contenitore-2 {
  background-color: black;
  display: flex;
  flex-wrap: wrap;
 }
 a {
  text-decoration: none;
 }
 .card-dc {
  flex: 0 0 25%;
 }
</style>
