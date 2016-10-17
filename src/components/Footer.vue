<template>
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
</template>

<style lang="scss" scoped>
  footer {
    text-align: center;
    ul {
      list-style-type: none;
      display: flex;
      flex-direction: column;
    }
    @media (min-width: 700px) {
      ul {
        flex-direction: row;
        justify-content: space-around;
      }
    }
  }
</style>
