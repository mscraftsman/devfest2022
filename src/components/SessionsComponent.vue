<template>
  <div>
    <div class="grid place-items-center md:place-items-start">
      <h2 class="mt-8 md:mt-10 text-3xl font-bold">Agenda</h2>
    </div>

    <div id="sessionizeComponent"></div>
  </div>
</template>

<script>
import postscribe from "postscribe";
export default {
  mounted() {
    postscribe(
      "#sessionizeComponent",
      `<script type="text/javascript" src="https://sessionize.com/api/v2/fruu0wnv/view/GridSmart"><\/script>`
    );
    setTimeout(() => {
      this.init();
    }, 1000);
  },
  methods: {
    init() {
      if (typeof sessionize !== "undefined") {
        sessionize.loader();
      }
    },
  },
};
</script>

<style scoped></style>
