<template>
  <div
    id="bio"
    class="w-full min-h-screen flex flex-col justify-center items-center"
  >
    <div class="w-1/2 py-4 flex flex-col items-center rounded-lg">
      <div class="w-32 h-32">
        <img
          src="~/assets/images/me.jpg"
          class="border-white border-2 rounded-full shadow-lg"
          alt="me.jpg"
          data-e2e="headshot-picture"
        />
      </div>
      <h1 class="text-white text-3xl my-4 text-center" data-e2e="name">
        Cameron Adams
      </h1>
      <span
        class="text-white text-md text-center leading-normal"
        data-e2e="bio"
      >
        Cameron Adams is an experienced web developer specializing in Hybrid
        applications. He has worked on multiple startup teams and developed
        multiple MVPs at a rapid pace. Other than time spent at work, Cameron
        uses his free time to create YouTube content (where he made his initial
        start) on technologies like ElectronJS, Vue.js, and the Ionic Framework.
      </span>
    </div>
    <SocialLinks />
  </div>
</template>

<script>
import SocialLinks from '@/components/social-links'
export default {
  components: {
    SocialLinks,
  },
}
</script>
b
