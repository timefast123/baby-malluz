<template>
  <div
    class="w-full bg-gradient-to-br from-pink-100 via-rose-200 to-fuchsia-300 text-gray-800 font-sans"
  >
    <!-- Hero Section -->
    <section class="pt-24 text-center">
      <h1 class="text-6xl font-extrabold tracking-wide mb-4">Malo Merlin</h1>
      <p class="text-xl font-light">Actress • Model • Dreamer</p>
    </section>

    <section class="pb-12 justify-center flex">
      <img src="./assets/profile.png" width="200" />
    </section>

    <!-- About Section -->
    <section class="max-w-4xl mx-auto py-20 px-8">
      <h2 class="text-4xl font-bold mb-8 text-center">About Me</h2>
      <p class="text-lg leading-relaxed text-center">
        With over 3 years of experience in professional modeling and acting, I
        bring elegance, creativity, and confidence to every project. My passion
        lies in expressing stories through visuals and performance, inspiring
        audiences with every appearance. Beyond the camera, I believe in
        continuous growth and a strong work ethic, making every collaboration
        unique and memorable.
      </p>
    </section>

    <!-- Gallery Section -->
    <section class="max-w-7xl mx-auto py-20 px-8">
      <h2 class="text-4xl font-bold mb-12 text-center">Portfolio</h2>
      <div class="grid grid-cols-4 gap-6">
        <img
          src="./assets/image0.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
        <img
          src="./assets/image1.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
        <img
          src="./assets/image2.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
        <img
          src="./assets/image3.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
        <img
          src="./assets/image4.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
        <img
          src="./assets/image5.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
        <img
          src="./assets/image6.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
        <img
          src="./assets/image7.png"
          alt="Portfolio Image"
          class="w-full h-72 object-cover rounded-2xl shadow-lg hover:scale-105 transform transition duration-500"
        />
      </div>
    </section>

    <!-- Contact Section -->
    <section class="bg-white/70 py-20">
      <div class="max-w-4xl mx-auto px-8 text-center">
        <h2 class="text-4xl font-bold mb-12">Get in Touch</h2>

        <div class="flex flex-col sm:flex-row justify-center gap-8">
          <!-- Instagram -->
          <a
            href="https://www.instagram.com/_i___s__h___a____"
            target="_blank"
            class="flex items-center gap-3 px-6 py-4 border border-gray-300 rounded-lg hover:bg-pink-100 transition"
          >
            <img
              src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/instagram.svg"
              alt="Instagram"
              class="w-6 h-6 fill-current text-pink-600"
            />
            <span class="text-lg font-medium text-gray-700"
              >@_i___s__h___a____</span
            >
          </a>

          <!-- Telegram -->
          <a
            href="https://t.me/Babynaluzz"
            target="_blank"
            class="flex items-center gap-3 px-6 py-4 border border-gray-300 rounded-lg hover:bg-blue-100 transition"
          >
            <img
              src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/telegram.svg"
              alt="Telegram"
              class="w-6 h-6 fill-current text-blue-500"
            />
            <span class="text-lg font-medium text-gray-700">@Babynaluzz</span>
          </a>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 text-center text-gray-600 text-sm">
      © 2025Malo Merlin | All Rights Reserved
    </footer>
  </div>
</template>

<script>
export default {
  name: "Portfolio",
};
</script>

<style></style>
