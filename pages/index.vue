<template>
  <body class="bg-gradient-to-t from-orange-400 to-red-600 select-none">
    <div
      class="widthius text-center justify-center align-center py-32"
      data-aos="zoom-in-up"
      data-aos-duration="800"
    >
      <h1 class="text-6xl sm:text-4xl">Aestas Flores 🌸</h1>
      <h3 class="text-4xl text-gray-200 mt-2 sm:text-3xl">
        Minik tohumların önce filizlendiği, <br />
        sonra çiçek açmış olduğu bir topluluk sunucusu.
      </h3>
      <p class="text-2xl mt-6 sm:text-xl">
        Neden mi katılmalısınız? <br />Çünkü
        <vue-typer
          class="text-2xl sm:text-xl"
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
        class="mt-12 w-64 h-64 px-5 py-5 sm:w-32 sm:h-32 mx-auto animate-pulse"
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
