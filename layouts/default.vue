<template>
  <div class="page-container radial-bg">
    <!-- <NavBar /> -->
    <transition name="slide-fade">
      <nuxt />
    </transition>
  </div>
</template>

<script>
// import NavBar from '@/components/nav-bar'
export default {
  components: {
    // NavBar
  },
}
</script>

<style>
html,
body {
  font-family: 'Lato', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  height: 100%;
}

.page-container {
  @apply min-h-screen min-w-full bg-cover;
}

.radial-bg {
  background: radial-gradient(
      circle closest-corner at center 50%,
      #222,
      black 90%
    )
    no-repeat;
}

.slide-fade-enter-active {
  transition: all 0.6s ease;
}
.slide-fade-leave-active {
  transition: all 1.6s cubic-bezier(1, 0.5, 0.8, 1);
}
.slide-fade-enter,
.slide-fade-leave-to {
  transform: translateY(20px);
  opacity: 0;
}
</style>
