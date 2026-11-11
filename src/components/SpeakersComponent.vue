<template>
  <div>
    <div class="grid place-items-center">
      <h2 class="mt-8 mb-8 md:mt-10 text-3xl font-bold">Speakers</h2>
    </div>

    <div id="sessionizeSpeakersComponent"></div>
  </div>
</template>

<script>
import postscribe from "postscribe";

export default {
  mounted() {
    postscribe(
      "#sessionizeSpeakersComponent",
      `<script type="text/javascript" src="https://sessionize.com/api/v2/fruu0wnv/view/SpeakerWall"><\/script>`
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
