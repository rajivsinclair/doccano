<template>
  <v-container>
    <v-layout
      column
      wrap
      class="my-5"
      align-center
    >
      <v-flex xs12 sm4 class="my-3">
        <div class="text-xs-center">
          <h2 class="headline">
<iframe src="https://docs.google.com/document/d/e/2PACX-1vQxeNvN5RM4fib7kNLWMZOhK73xHK9j0hMbOxPikcnYP_rgqjxPXPq_zLQW9MtHMn9ptgJa3Fo1pTgG/pub?embedded=true"></iframe>
          </h2>
        </div>
      </v-flex>
      <!-- <v-flex xs12>
        <v-container grid-list-xl>
          <v-layout wrap align-center>
            <v-flex
              v-for="(item, index) in featureCards"
              :key="index"
              xs12
              md4
            >
              <feature-card
                :image-src="require(`~/assets/${item.imageSrc}`)"
                :title="item.title"
                :text="item.text"
              />
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex> -->
    </v-layout>
  </v-container>
</template>

// <script lang="ts">
// import Vue from 'vue'
// import FeatureCard from './FeatureCard.vue'

// export default Vue.extend({
//   components: {
//     FeatureCard
//   },

//   data() {
//     return {
//       featureCards: [
//         {
//           imageSrc: 'feature3.png',
//           title: this.$t('home.featuresTitle1'),
//           text: this.$t('home.featuresText1')
//         },
//         {
//           imageSrc: 'feature2.png',
//           title: this.$t('home.featuresTitle2'),
//           text: this.$t('home.featuresText2')
//         },
//         {
//           imageSrc: 'feature1.png',
//           title: this.$t('home.featuresTitle3'),
//           text: this.$t('home.featuresText3')
//         }
//       ]
//     }
//   }
// })
// </script>
