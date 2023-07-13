<template>
  <div
    class="offset-header font-IBM font-semibold text-white text-[2.625rem] text-center flex items-center justify-center my-20"
  >
    <h1 class="max-w-lg">
      <span class="offset-header offset-header-odd">
        <span>Make brand identities</span>
      </span>
      <span class="offset-header offset-header-odd">
        <span>from scratch and help big</span>
      </span>
      <span class="offset-header offset-header-odd">
        <span> brands stay mighty</span>
      </span>
    </h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
span.offset-header {
  display: block;
  overflow: hidden;
}

span.offset-header > span {
  animation-name: slideUp;
  animation-duration: 4s;
  animation-timing-function: cubic-bezier(0, 0, 0.2, 1);
  display: block;
}

.offset-header-odd > span {
  animation-delay: 0s;
  animation-fill-mode: both;
}

@keyframes slideUp {
  0%,
  50% {
    transform: translateY(100%);
    opacity: 0;
  }

  60%,
  100% {
    transform: translateY(0);
    opacity: 1;
  }
}
</style>
