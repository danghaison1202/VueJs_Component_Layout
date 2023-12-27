<template>
  <div class="home">
    <h1>Dynamic FE Component</h1>
    <div class="card">
      <div class="card-info">
        <p class="title">Magic Card</p>
      </div>
    </div>
    <div class="card2">
      <p class="card-title">Product Name</p>
      <p class="small-desc">
        VueJs Competency Test
      </p>
      <div class="go-corner">
        <div class="go-arrow">→</div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
}
</script>
