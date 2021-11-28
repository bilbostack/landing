<template>
  <div class="body">
    <p>
      <a href="https://github.com/bilbostack" target="_blank">
          <img :src="$withBase('/github-logo.png')" alt="github-logo">
      </a>
      <a href="mailto:info@bilbostack.com" target="_blank">
          <img :src="$withBase('/mail-logo.png')" alt="mailto-logo">
      </a> 
      <a href="https://twitter.com/bilbostack" target="_blank">
          <img :src="$withBase('/twitter-logo.png')" alt="twitter-logo">
      </a>
    </p>
  </div>
</template>

<style scoped>
.body {
  margin: auto;
  width: 70%;
  padding: 10px;
  text-align: center;
}

img {
    width: 50px;
    height: 50px;
}
</style>
