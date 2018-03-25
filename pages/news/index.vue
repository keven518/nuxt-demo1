<!--  -->
<template>
  <div>
    <h1>News Index page</h1>
    <p>NewsID: {{$route.params.newsId}}</p>
    <ul>
      <li><a href="/">news</a></li>
      <li><a href="/news/123">news-123</a></li>
      <li><a href="/news/456">news-456</a></li>
      <li><nuxt-link :to="{name:'news-id', params:{id:789}}">NEWS-789</nuxt-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  transition: 'test',
  
  props: [],

  data () {
    return {
    };
  },

  created(){},

  mounted(){},

  watch: {},

  computed: {},

  methods: {},

  components: {}
}

</script>
<style scoped>
</style>