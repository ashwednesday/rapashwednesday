<template>
  <nav>
    <ul>
      <li>
        <img class="social-icon" src="../assets/facebook.png" alt="Facebook">
      </li>
      <li>
        <img class="social-icon" src="../assets/twitter.png" alt="Twitter">
      </li>
      <li>
        <img class="social-icon" src="../assets/instagram.png" alt="Instagram">
      </li>
      <li>          
        <img class="social-icon" src="../assets/soundcloud.png" alt="Sound Cloud">
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
  nav {
    max-width: 20rem;
    margin: 0 auto;
    padding-top: 5%;

    img {
      height: 70%;
    }

    ul {
      display: flex;
      justify-content: space-around;
    }
  }
</style>
