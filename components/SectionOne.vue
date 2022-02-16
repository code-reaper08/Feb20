<template>
  <div class="home__wrapper">
    <div
      class="text__wishes flex justify-center items-center md:items-start md:justify-center h-[90vh]"
    >
      <h1
        class="text-8xl lg:text-[20rem] text-yellow-200 font-semibold flex flex-col md:flex-row w-[65vw] md:w-auto md:space-x-5 space-y-5"
      >
        <span
          class="hover:text-cyan-400 md:hover:bg-black transition-all flex items-center md:block relative mb-10 md:mb-0"
        >
          அ
          <p class="text-sm ml-5 md:static absolute right-0">
            Adorable
            <!-- A -->
          </p>
        </span>
        <span
          class="hover:text-cyan-500 md:hover:bg-black transition-all flex items-center md:block relative"
        >
          கி
          <p class="text-sm ml-5 absolute right-0 md:static">
            Kingly
            <!-- ki -->
          </p>
        </span>
        <span
          class="hover:text-cyan-600 md:hover:bg-black transition-all flex items-center md:block relative"
        >
          <p class="mr-0">ரா</p>
          <p class="text-sm ml-5 absolute right-0 md:static">
            intrepid
            <!-- rā -->
          </p>
        </span>
        <!-- <span
          class="hover:text-cyan-700 hover:bg-black rounded-3xl transition-all flex items-center md:block relative"
        >
          R
          <p class="text-sm ml-5 absolute right-0 md:static">ravishing</p>
        </span>
        <span
          class="hover:text-cyan-800 hover:bg-black rounded-3xl transition-all flex items-center md:block relative"
        >
          A
          <p class="text-sm absolute right-0 md:static">Attentive</p>
        </span> -->
      </h1>
    </div>
    <div class="navigator__pane flex justify-center">
      <p class="text-white italic text-sm font-semibold mx-auto">
        Wish me a chickenfull' birthday
      </p>
      <NuxtLink to="/me">
        <p
          class="text-white italic text-sm font-semibold mr-10 md:bg-black rounded-lg px-2 py-1 cursor-pointer"
        >
          See me →
        </p>
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
};
</script>
<style scoped>
.home__wrapper {
  background-color: black;
  background-position: left;
  /* background-blend-mode: luminosity; */
  background-image: url("https://monophy.com/media/3oxHQy8tANyw2Wx7Dq/monophy.gif");
  background-repeat: no-repeat;
  background-size: cover;
  width: 100vw;
  height: 100vh;
  filter: contrast(120%);
}
/* medium and above */
@media (min-width: 768px) {
  .home__wrapper {
    /* background-image: url("https://user-images.githubusercontent.com/64256342/153702030-2efa55ff-5c5e-4373-9bc6-1a85119a49d8.jpg"); */
    background-color: black;
    background-image:
  /* url("https://cdn.pixabay.com/photo/2017/03/23/15/10/background-2168549_1280.jpg"), */
    /* url("https://wallpaper.dog/large/10777675.jpg"); */
      url("https://img1.goodfon.com/wallpaper/nbig/6/52/rentgen-chelovek-sobaka-povodok.jpg"),
      /* url("https://cdn.shopify.com/s/files/1/0270/3038/8823/t/10/assets/pf-acdd72d9--GIF2filmburn.gif?v=1621530142"); */
        url("https://motionstacks-strapi-images.s3.amazonaws.com/light_leak_01_76b090dea1.gif");
    background-position: center;
    background-blend-mode: screen;
    background-repeat: no-repeat;
    background-size: contain, cover;
    width: 100vw;
    height: 100vh;
    filter: contrast(120%);
  }
}
</style>
