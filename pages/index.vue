<template>
  <body class="bg-gradient-to-t from-orange-400 to-red-600 select-none">
    <div
      class="widthius text-center justify-center align-center py-32"
    >
      <h1 class="text-5xl md:text-6xl">Aestas Flores 🌸</h1>
      <h3 class="text-3xl text-gray-200 mt-2 md:text-4xl">
        Minik tohumların önce filizlendiği, <br />
        sonra çiçek açmış olduğu bir topluluk sunucusu.
      </h3>
      <p class="text-base mt-6 md:text-2xl">
        Neden mi katılmalısınız? <br />Çünkü
        <vue-typer
          class="text-base md:text-2xl"
          :text="about.info"
          :repeat="Infinity"
          :shuffle="false"
          initial-action="typing"
          :pre-type-delay="70"
          :type-delay="55"
          :pre-erase-delay="2000"
          :erase-delay="250"
          erase-style="select-all"
          :erase-on-complete="false"
          caret-animation="blink"
        />
      </p>

      <img
        src="../static/logo_black.svg"
        class="transform scale-100 mt-12 w-32 h-32 px-5 py-5 md:w-64 md:h-64 mx-auto animate-pulse"
      />
    </div>
  </body>
</template>

<style>
.widthius {
  margin: 0 auto;
  max-width: 850px;
}

img {
  margin: 0 auto;
}
</style>

<script>
export default {
  name: "",
  props: {
    about: {
      type: Object,
      required: true,
      default: function () {
        return {
          info: [
            "saygı çerçevesinde konuşuruz.",
            "tohumlarımızı önemseriz.",
            "ayda bir çekilişler sizinle.",
            "başka tohumlarla filizlenebilirsiniz.",
            "yeni türde çiçekler bulabilirsiniz.",
          ],
        };
      },
    },
  },
};
</script>

<!-- data-aos="zoom-in-up"
      data-aos-duration="800" -->
