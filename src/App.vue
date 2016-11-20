<template>
  <div id="app">
    <div class='store-row'>
      <a class='store-cta' href='https://squareup.com/store/rapashwednesday'>
        Merch
      </a>
    </div>
    <h1>
      ASH
      <br />
      <span class="h1-subtitle">
        Wednesday
      </span>
    </h1>
    <SocialIcons></SocialIcons>
    <FeaturedAlbum></FeaturedAlbum>
    <hr />
    <LatestSingles></LatestSingles>
    <hr />
    <Shows></Shows>
    <hr />
    <Footer></Footer>
  </div>
</template>

<style src="./styles/normalize.css"></style>
<style src="./styles/global.scss" lang="scss"></style>

<style lang="scss" scoped>
  .store-row {
    width: 100%;
    display: flex;
    justify-content: flex-end;
  }
  .store-cta {
    text-transform: uppercase;
    width: 100px;
    padding: 8px;
    color: #fff;
    border: 2px solid #fff;
    border-radius: 5px;
    text-align: center;
    outline: none;
    text-decoration: none;
  }
</style>

<script>
  import FeaturedAlbum from './components/FeaturedAlbum'
  import SocialIcons from './components/SocialIcons'
  import LatestSingles from './components/LatestSingles'
  import Shows from './components/Shows'
  import Footer from './components/Footer'

  export default {
    components: {
      FeaturedAlbum,
      SocialIcons,
      LatestSingles,
      Shows,
      Footer
    }
  }
</script>
