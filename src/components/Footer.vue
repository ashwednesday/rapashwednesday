<template>
  <footer>
    <ul>
      <li>
        <a href="https://www.facebook.com/rapashwednesday/">Facebook</a>
      </li>
      <li>
        <a href="https://twitter.com/rapashwednesday">Twitter</a>
      </li>
      <li>
        <a href="https://www.instagram.com/rapashwednesday/">Instagram</a>
      </li>
      <li>
        <a href="https://soundcloud.com/rapashwednesday/">Soundcloud</a>
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
