<template>
  <div class="hello">
    <iframe src="https://assembly.haoxp.xyz" title="webassembly" width="1000" height="700">
      <p>Your browser does not support iframes.</p>
    </iframe>
  </div>
</template>

<script>
export default {
  name: 'test',
  data() {
    return {
      msg: ''
    }
  },
  created: function () {
    // return
    // let gameInstance = UnityLoader.instantiate(
    //   'gameContainer', './Assembly/Build/web.json', {
    //     onProgress: UnityProgress
    //   }
    // )
    // console.log(gameInstance)
  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
iframe {
  border: none;
  overflow: hidden;
}
</style>
