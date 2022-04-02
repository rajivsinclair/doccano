<template>
  <section>
   
  </section>
</template>

-<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      items: [
        { title: this.$t('home.demoNER'), link: 'named-entity-recognition' },
        { title: this.$t('home.demoSent'), link: 'sentiment-analysis' },
        { title: this.$t('home.demoTranslation'), link: 'translation' },
        { title: this.$t('home.demoTextToSQL'), link: 'text-to-sql' }
      ]
    }
  }
})
</script>