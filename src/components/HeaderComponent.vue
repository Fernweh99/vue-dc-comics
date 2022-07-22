<template>
  <header>
    <nav class="container">
      <div class="col-img h-100">
        <img src="../assets/img/dc-logo.png" alt="Dc Logo">
      </div>
      <div class="col-link h-100">
        <ul class="h-100">
          <li class="h-100" v-for="link in links" :key="link.text">
            <a :href="link.url" :class="{'active' :link.current}">{{ link.text }}</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
  data() {
    return {
      links: [
        {
          text: 'Characters',
          url: '#',
          current: false,
        },
        {
          text: 'Comics',
          url: '#',
          current: true,
        },
        {
          text: 'Movies',
          url: '#',
          current: false,
        },
        {
          text: 'TV',
          url: '#',
          current: false,
        },
        {
          text: 'Games',
          url: '#',
          current: false,
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false,
        },
        {
          text: 'Videos',
          url: '#',
          current: false,
        },
        {
          text: 'Fans',
          url: '#',
          current: false,
        },
        {
          text: 'News',
          url: '#',
          current: false,
        },
        {
          text: 'Shop',
          url: '#',
          current: false,
        },
      ],
    }
  }
}
</script>

<style lang="scss" scoped>
  header {
    background-color: #fff;
    margin-top: 15px
  }
  nav {
    display: flex;
    width: 100%;
    height: 90px;
    justify-content: space-between;
  }
  img {
    height: 100%;
    padding: 10px;
  }
  .col-link a{
   color: #707070;
   text-transform: uppercase;
   margin-left:25px;
   font-size: 12px;
   height:100%;
   line-height: 90px;
   font-weight: bold;
   border-bottom: 2px solid transparent;
  }
  .col-link a.active,
  .col-link a:hover {
    color: #0082F9;
    border-bottom: 3px solid #0082F9;
  }
  
</style>