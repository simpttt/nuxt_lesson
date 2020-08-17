<template>
  <div>
    <nuxt-link to="/about">ABOUT</nuxt-link>
    <section>
      <sample-component :title="indexTitle">
        <div slot="named">
          named slot
        </div>
      </sample-component>
    </section>
  </div>
</template>

<script>
import SampleComponent from '~/components/SampleComponent.vue'
export default {
  components: {
    SampleComponent,
  },
  data() {
    return {
      indexTitle: 'aaaaaaaaaa',
    }
  },
  layout: 'dark',
}
</script>

<style></style>
