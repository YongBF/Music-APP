<template>
  <div id="app">
    <m-header/>
    <m-tab/>
    <keep-alive>
      <router-view/>
    </keep-alive>
    <play></play>
  </div>
</template>

<script>
import MHeader from 'components/m-header/m-header'
import MTab from 'components/m-tab/m-tab'
import Play from 'components/player/play'
export default {
  name: 'App',
  components: {
    MHeader,
    MTab,
    Play
  }
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>
