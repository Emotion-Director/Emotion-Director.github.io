<script>
import Title from './sections/Title.vue'
import Abstract from './sections/Abstract.vue'
import Carousel from './sections/Carousel.vue'
import Pipeline from './sections/Pipeline.vue'
import Result from './sections/Result.vue'

export default {
  components: {
    Title,
    Carousel,
    Abstract,
    Pipeline,
    Result,
  }
}
</script>

<template>
  <Title/>
  <Carousel/>
  <Abstract/>
  <Pipeline/>
  <Result/>
</template>