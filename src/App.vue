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
    <LatestTracks></LatestTracks>
    <hr />
    <Shows></Shows>
    <hr />
    <Footer></Footer>
  </div>
</template>

<style src="./styles/global.scss" lang="scss"></style>

<script>
  import Hello from './components/Hello'
  import FeaturedAlbum from './components/FeaturedAlbum'
  import SocialIcons from './components/SocialIcons'
  import LatestTracks from './components/LatestTracks'
  import Shows from './components/Shows'
  import Footer from './components/Footer'

  export default {
    components: {
      Hello,
      FeaturedAlbum,
      SocialIcons,
      LatestTracks,
      Shows,
      Footer
    }
  }
</script>
