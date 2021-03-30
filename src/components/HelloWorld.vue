<template>
  <div class="hello">
    <img alt="Burazer" srcset="./../assets/burazer.png, ./../assets/burazer@2x.png 2x">
    <div>
      <h1 style="display: block;line-height: 1.2"><span style="font-weight: bold">Rivers</span> feat Catrin Noise is now available!</h1>
      <h3>Listen now on your favorite streaming services</h3>
    </div>
    
    <ul>
      <li><a href="https://open.spotify.com/track/6hKxKDZQSh4chjiyzTGnsQ?si=vCa6aG31TXm_gqbOR9sSMA" target="_blank" rel="noopener">Spotify</a></li>
      <li><a href="https://music.apple.com/us/album/rivers-feat-catrin-noise-single/1559376507" target="_blank" rel="noopener">Apple Music</a></li>
      <li><a href="https://music.youtube.com/watch?v=be3Lf9MgztM&feature=share" target="_blank" rel="noopener">YouTube Music</a></li>
    </ul>

    <p>2021 &copy; RevolutionsRecords.com</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  padding: 2rem;
  box-sizing: border-box;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
