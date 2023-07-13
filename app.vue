<template>
  <div class="box">
    <NuxtPage />
  </div>
</template>

<style scoped>
.box {
  height: 100vh;
  background-color: rgba(0, 0, 0, 0.88) !important;
  background: 
  /* Horizontal Line */ radial-gradient(
        296.35px at 50% calc(100% + 255px),
        #0000 calc(100% - -2px),
        rgb(251, 251, 251, 0.6) calc(100% - -2px) 99%,
        #0000 101%
      )
      calc(50% - 300px) calc(50% - 73.5px + 0.5px) / 600px 151px,
    radial-gradient(
        296.35px at 50% -255px,
        #0000 calc(100% - -2px),
        rgb(251, 251, 251, 0.6) calc(100% - -2px) 99%,
        #0000 101%
      )
      50% calc(50% + 71.5px) / 600px 151px,
    /* Vertical Line */
      radial-gradient(
        296.35px at calc(100% + 255px) 50%,
        #0000 calc(100% - -2px),
        rgb(251, 251, 251, 0.6) calc(100% - -2px) 99%,
        #0000 101%
      )
      calc(50% - 73.5px + 0.5px) calc(50% - 300px) / 151px 600px,
    radial-gradient(
        296.35px at -255px 50%,
        #0000 calc(100% - -2px),
        rgb(251, 251, 251, 0.6) calc(100% - -2px) 99%,
        #0000 101%
      )
      calc(50% + 71.5px) 50%/151px 600px;
}
</style>
