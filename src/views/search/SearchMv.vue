<template>
  <div class="search-mv">
    <video-list :videoList="searchData"></video-list>
  </div>
</template>

<script>
import VideoList from '../../components/common/VideoList.vue'
export default {
  name: "SearchMv",
  props: {
    searchData: {
      type: Array,
      default () {
        return []
      }
    }
  },
  components: {
    VideoList
  }
}
</script>

<style>
</style>