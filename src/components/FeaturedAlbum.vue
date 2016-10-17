<template>
  <section class="featured-album">
    <header>
      <h2> Ugly On Purpose Mixtape Now Available</h2>
      <h3>Download EP or listen on Soundcloud.</h3>
    </header>
    <div class="featured-album__items">
      <div class="download-album">
        <div class="download-album-cover">
          <img class="album-cover" src="../assets/ugly-on-purpose-cover.png" alt="Ugly On Purpose Album Cover">
        </div>
        <button>Download EP</button>
      </div>

      <div class="soundcloud-widget">
        <iframe scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/153720446&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>
      </div>

    </div>
  </section>
</template>

<style lang="scss" scoped>
  .featured-album {
    text-align: center;
  }

  .featured-album__items {
    display: flex;
    flex-direction: column-reverse;
    
    @media (min-width: 700px) {
      flex-direction: row;
      justify-content: space-around;
    }

    img {
      width: 100%
    }

    @media (min-width: 700px) {
      img {
        height: 90%;
        width: auto;
      }
    }
  }

  button {
    width: 40%;
    display: inline-block;
    height: 38px;
    padding: 0 30px;
    color: #555;
    text-align: center;
    font-size: 11px;
    font-weight: 600;
    line-height: 38px;
    letter-spacing: .1rem;
    text-transform: uppercase;
    text-decoration: none;
    white-space: nowrap;
    background-color: transparent;
    border-radius: 4px;
    border: 1px solid #bbb;
    cursor: pointer;
    box-sizing: border-box;
  }

  button:hover, button:focus {
    color: #333;
    border-color: #888;
    outline: 0; 
  }

  @media (min-width: 700px) {
    button {
      width: 60%;
    }
  }

   @media (min-width: 750px) {
    .soundcloud-widget {
      width: 50%;
      margin: 0;
    }
    iframe {

    }
  }
</style>
