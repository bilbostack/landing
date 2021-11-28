<template>
  <div class="social-links">
    <p>
      <a href="mailto:info@bilbostack.com" target="_blank">
          <img :src="$withBase('/mail-logo-white.png')" alt="mailto-logo">
      </a> 
      <a href="https://twitter.com/bilbostack" target="_blank">
          <img :src="$withBase('/twitter-logo-white.png')" alt="twitter-logo">
      </a>
      <a href="https://t.me/bilbostack20" target="_blank">
          <img :src="$withBase('/telegram-logo-white.png')" alt="telegram-logo">
      </a>
      <a href="https://github.com/bilbostack" target="_blank">
          <img :src="$withBase('/github-logo-white.png')" alt="github-logo">
      </a>
    </p>
  </div>
</template>

<style scoped>
.social-links {
  margin: auto;
  width: 70%;
  padding: 10px;
  text-align: center;
}

img {
    width: 30px;
    height: 30px;
}
</style>
