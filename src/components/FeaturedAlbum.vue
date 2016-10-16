<template>
  <section class="featured-album">
    <h2> Ugly On Purpose Mixtape Now Available</h2>
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
    <p>Download EP or listen to on Soundcloud.</p>
  </section>
</template>

<style lang="scss" scoped>
  .featured-album {
    text-align: center;
  }

  .featured-album__items {
    display: flex;
    flex-direction: column;
    
    @media (min-width: 700px) {
      flex-direction: row;
      justify-content: center;
    }

    img {
      height: 90%;
    }

    button {
      padding: .7rem;
      width: 40%;
    }

    @media (min-width: 700px) {
      button {
        padding: .7rem;
        width: 60%;
      }
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
