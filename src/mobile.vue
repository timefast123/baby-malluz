<template>
  <div
    class="w-full min-h-screen bg-gradient-to-br from-pink-100 via-rose-200 to-fuchsia-300 text-gray-800 font-sans"
    data-aos="fade-in"
  >
    <!-- Hero Section -->
    <section class="pt-16 text-center px-4">
      <h1
        class="text-4xl font-extrabold tracking-wide mb-3"
        data-aos="fade-up"
        data-aos-delay="100"
      >
        Malo Merlin
      </h1>
      <p class="text-lg font-light" data-aos="fade-up" data-aos-delay="200">
        Actress • Model • Dreamer
      </p>
    </section>

    <section
      class="flex justify-center my-6"
      data-aos="zoom-in"
      data-aos-delay="300"
    >
      <img
        src="./assets/profile.png"
        class="w-40 h-40 rounded-full shadow-lg object-cover"
      />
    </section>

    <!-- About Section -->
    <section class="max-w-md mx-auto py-10 px-4 text-center">
      <h2 class="text-3xl font-bold mb-6" data-aos="fade-up">About Me</h2>
      <p
        class="text-base leading-relaxed"
        data-aos="fade-up"
        data-aos-delay="100"
      >
        With over 3 years of experience in professional modeling and acting, I
        bring elegance, creativity, and confidence to every project. I’m
        passionate about storytelling through visuals, and love to inspire
        audiences with each performance.
      </p>
    </section>

    <!-- Portfolio Gallery -->
    <section class="px-4 py-12">
      <h2 class="text-3xl font-bold mb-8 text-center" data-aos="fade-up">
        Portfolio
      </h2>
      <div
        class="grid grid-cols-2 gap-4 sm:grid-cols-3 md:grid-cols-4"
        data-aos="zoom-in-up"
      >
        <img
          src="./assets/image0.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
        <img
          src="./assets/image1.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
        <img
          src="./assets/image2.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
        <img
          src="./assets/image3.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
        <img
          src="./assets/image4.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
        <img
          src="./assets/image5.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
        <img
          src="./assets/image6.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
        <img
          src="./assets/image7.png"
          alt="Portfolio"
          class="w-full h-40 sm:h-48 object-cover rounded-xl shadow-md hover:scale-105 transition-transform duration-500"
        />
      </div>
    </section>

    <!-- Contact Section -->
    <section class="bg-white/70 py-10 px-6">
      <div class="max-w-md mx-auto text-center">
        <h2 class="text-3xl font-bold mb-8" data-aos="fade-up">Get in Touch</h2>

        <div class="flex flex-col gap-4">
          <a
            href="https://www.instagram.com/_i___s__h___a____"
            target="_blank"
            class="flex items-center justify-center gap-3 px-4 py-3 border border-gray-300 rounded-lg hover:bg-pink-100 transition"
            data-aos="fade-left"
          >
            <img
              src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/instagram.svg"
              class="w-5 h-5"
            />
            <span class="text-base font-medium text-gray-700">
              @_i___s__h___a____
            </span>
          </a>

          <a
            href="https://t.me/Babynaluzz"
            target="_blank"
            class="flex items-center justify-center gap-3 px-4 py-3 border border-gray-300 rounded-lg hover:bg-blue-100 transition"
            data-aos="fade-right"
          >
            <img
              src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/telegram.svg"
              class="w-5 h-5"
            />
            <span class="text-base font-medium text-gray-700">@Babynaluzz</span>
          </a>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="py-6 text-center text-gray-600 text-sm">
      © 2025 Malo Merlin | All Rights Reserved
    </footer>
  </div>
</template>

<script>
export default {
  name: "PortfolioMobile",
  mounted() {
    import("aos").then((AOS) => {
      AOS.init({ once: true });
    });
  },
};
</script>

<style scoped>
@import "aos/dist/aos.css";
</style>
