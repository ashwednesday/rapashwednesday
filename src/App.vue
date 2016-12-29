<template>
  <div id="app">
    <div class='hero'>
      <h1>ASH<br /><span class="h1-subtitle">Wednesday</span></h1>
      <nav>
        <ul>
          <li>
            <a href='#about'>About</a>
          </li>
          <li>
            <a href='#shows'>Shows</a>
          </li>
          <li>
            <a href='https://squareup.com/store/rapashwednesday'>Merch</a>
          </li>
        </ul>
      </nav>
    </div>

    <SocialIcons></SocialIcons>
    <FeaturedAlbum></FeaturedAlbum>
    <hr />
    <LatestSingles></LatestSingles>
    <hr />
    <Shows></Shows>
    <hr />
    <About></About>
    <hr />
    <Footer></Footer>
  </div>
</template>

<style src="./styles/normalize.css"></style>
<style src="./styles/global.scss" lang="scss"></style>

<style lang="scss" scoped>
  .hero {
    display: flex; 
    justify-content: center;
    max-width: 330px;
    margin: 0 auto;

    a {
      color: white;
      text-decoration: none;
    }

    ul {
      margin-top: -1.5rem;
      padding-left: 4rem;
    }
  }
  
  .store-row {
    width: 100%;
    display: flex;
    justify-content: flex-end;
  }
  .store-cta {
    text-transform: uppercase;
    width: 70px;
    margin-bottom: 20px;
    padding: 8px;
    color: #fff;
    border: 2px solid #fff;
    border-radius: 5px;
    text-align: center;
    outline: none;
    text-decoration: none;

    @media (min-width: 400px) {
      width: 100px;
      margin-bottom: 0;
    }
  }
</style>

<script>
  import FeaturedAlbum from './components/FeaturedAlbum'
  import SocialIcons from './components/SocialIcons'
  import LatestSingles from './components/LatestSingles'
  import Shows from './components/Shows'
  import About from './components/About'
  import Footer from './components/Footer'

  export default {
    components: {
      FeaturedAlbum,
      SocialIcons,
      LatestSingles,
      Shows,
      About,
      Footer
    }
  }
</script>
