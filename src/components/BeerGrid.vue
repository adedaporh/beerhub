<template>
    <div class="tile is-ancestor">
  <div class="tile">
    <!-- Add content or other tiles -->
    <base-card>
  <template v-slot:default>
    <div class="content">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      Phasellus nec iaculis mauris. <a>@bulmaio</a>.
      <a href="#">#css</a> <a href="#">#responsive</a>
      <br>
      <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
    </div>
  </template>
  <template v-slot:cardFooter>
    <a href="#" class="card-footer-item"><i class="fas fa-thumbs-up"></i></a>
    <a href="#" class="card-footer-item"><i class="fas fa-thumbs-down"></i></a>
    <a href="#" class="card-footer-item"><i class="fas fa-retweet"></i></a>

  </template>
  </base-card>
  </div>
  
    </div>
  
</template>

<script>
import BaseCard from './UI/BaseCard.vue'
export default {
  components: { BaseCard },
    name:'BeerGrid'
}
</script>

<style>

</style>