<template>
  <div id="social-links" class="w-full mt-4 flex justify-center items-center">
    <a href="https://gitlab.com/cameronadams777" class="mx-3 grow">
      <GitlabIcon class="text-white hover:text-grey" size="2x" />
    </a>
    <a href="https://youtube.com/maxchaor" class="mx-3 grow">
      <YoutubeIcon class="text-white hover:text-grey" size="2x" />
    </a>
    <a href="https://twitter.com/cameronadams777" class="mx-3 grow">
      <TwitterIcon class="text-white hover:text-grey" size="2x" />
    </a>
    <a
      href="https://www.linkedin.com/in/cameron-adams-a6653ab9"
      class="mx-3 grow"
    >
      <LinkedinIcon class="text-white hover:text-grey" size="2x" />
    </a>
  </div>
</template>

<script>
import {
  GitlabIcon,
  LinkedinIcon,
  TwitterIcon,
  YoutubeIcon,
} from 'vue-feather-icons'
export default {
  components: {
    GitlabIcon,
    LinkedinIcon,
    TwitterIcon,
    YoutubeIcon,
  },
}
</script>

<style scoped>
.grow {
  transition: all 0.2s ease-in-out;
}

.grow:hover {
  transform: scale(1.2);
}
</style>
