<template>
  <div id="app">

    <h1>ASH<br /><span class="h1-subtitle">Wednesday</span></h1>

    <nav>
      <ul>
        <li>
          <img class="social-icon" src="./assets/facebook.svg" alt="Facebook">
        </li>
        <li>
          <img class="social-icon" src="./assets/twitter.svg" alt="Twitter">
        </li>
        <li>          
          <img class="social-icon" src="./assets/instagram.svg" alt="Instagram">
        </li>
        <li>          
          <img class="social-icon" src="./assets/soundcloud.svg" alt="Sound Cloud">
        </li>
      </ul>
    </nav>

    <section class="featured-album">
      <h2> Ugly On Purpose Mixtape Now Available</h2>
      <div class="featured-album__items">
        <div class="download-album">
          <div class="download-album-cover">
            <img class="album-cover" src="./assets/ugly-on-purpose-cover.png" alt="Ugly On Purpose Album Cover">
          </div>
          <button>Download EP</button>
        </div>
        <div class="soundcloud-widget">
          <iframe scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/153720446&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>
        </div>
      </div>
      <p>Download EP or listen to on Soundcloud.</p>
    </section>

    <hr />
    <footer>
      <ul>
        <li>
          Facebook
        </li>
        <li>
          Twitter
        </li>
        <li>
          Instagram
        </li>
        <li>
          Soundcloud
        </li>
      </ul>
      <p>
        Contact: rapashwednesday@gmail.com
      </p>
    </footer>
  </div>
</template>

<style src="./styles/global.scss" lang="scss"></style>

<script>
import Hello from './components/Hello'

export default {
  components: {
    Hello
  }
}
</script>
