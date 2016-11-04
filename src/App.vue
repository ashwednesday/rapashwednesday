<template>
  <div id="app">
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
