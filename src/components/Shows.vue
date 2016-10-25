<template>  
  <article class="shows">
    <header>
      <h2>Shows</h2>
    </header>

    <section class="upcoming">
      <h3>Upcoming:</h3>
      <ul>
        <li>
          <i>No upcoming shows scheduled.</i>
        </li>
      </ul>
    </section>

    <section class="past">
      <h3>Past:</h3>
      <ul>
        <li>
          <time>Saturday, September 17th 2016</time>
          <h4>PARTY in my Backyard (ft. Ash Wednesday, Fess Grandiose + More)</h4>
          <p>
            <b>Location:</b> 3187-3199 N Kimball Ave, Chicago, IL 60618, USA
          <p>
        </li>
      </ul>
    </section>
  </article>
</template>

<style lang="scss" scoped>
  header {
    text-align: center;
  }

  ul {
    text-align: left;
  }

  time {
    font-size: 1rem;
  }

  p {
    color: lighten(white, 40%);
    font-size: 1.2rem;
  }
</style>
