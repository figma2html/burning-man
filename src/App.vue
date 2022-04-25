<template>
  <header class="h-screen">
    <div class="container mx-auto h-full text-white">
      <div class="flex flex-wrap flex-row py-8 md:py-12 items-center font-bold text-sm md:text-lg uppercase">
        <div class="flex items-center">
          <img src="./assets/images/logo.svg" alt="logo">
          <ul class="flex flex-wrap">
            <li class="ml-4 md:ml-20">Home</li>
            <li class="ml-4 md:ml-10">About</li>
            <li class="ml-4 md:ml-10">Tickets</li>
            <li class="ml-4 md:ml-10">Contacts</li>
          </ul>
        </div>
        <p class="ml-auto">+1 893 839-23-64</p>
      </div>
      <div class="absolute md:inset-y-1/3 inset-y-1/2 uppercase">
        <h2 class="text-lg md:text-5xl font-bold">Not tne event. The life</h2>
        <h1 class="text-5xl md:text-9xl font-bold">Burning MAN</h1>
        <button class="mt-2 md:mt-6 text-white border-2 py-2 md:py-4 md:px-8 px-4 uppercase font-bold">Book the
          tickets
        </button>
      </div>
    </div>
  </header>
  <section class="container mx-auto mt-28">
    <div class="flex flex-wrap flex-row">
      <h2 class="text-6xl font-bold mb-20 uppercase">About the event</h2>
      <div class="flex flex-wrap -m-4">
        <div class="p-4 md:w-1/2 w-full">
          <h4 class="text-4xl font-bold mb-12 uppercase">Rebuilding the society</h4>
          <p>Burning Man is a network of people inspired by the values reflected in the Ten Principles and united in the
            pursuit of a more creative and connected existence in the world. Throughout the year we work to build Black
            Rock City, home of the largest annual Burning Man gathering, and nurture the distinctive culture emerging
            from that experience. </p>
        </div>
        <div class="p-4 md:w-1/2 w-full">
          <h4 class="text-4xl font-bold mb-12 uppercase">This drives us</h4>
          <p class="mb-12">Burning Man Project will bring experiences to people in grand, awe-inspiring and joyful ways
            that lift the
            human spirit, address social problems, and inspire a sense of culture, community, and civic engagement.
            Burning Man provides infrastructural tools and frameworks to support local communities in applying the Ten
            Principles through six interconnected program areas, including Arts, Civic Involvement, Culture, Education,
            Philosophical Center, and Social Enterprise.</p>
        </div>
        <div class="p-4 md:w-1/2 w-full">
          <div class="flex flex-wrap">
            <img class="md:w-1/2 w-full" src="./assets/images/image1.bmp">
            <img class="md:w-1/2 w-full" src="./assets/images/image2.bmp">
          </div>
        </div>
        <div class="p-4 md:w-1/2 w-full">
          <img class="w-full" src="./assets/images/image3.bmp">
        </div>
      </div>
    </div>
  </section>
  <footer class="container mx-auto flex md:flex-row flex-col text-base mt-28 mb-12">
    <p class="mr-12">©1989-2020 burning man project</p>
    <p>WAYUP & Андрей Гаврилов</p>
  </footer>
</template>

<style>
header {
  background-image: url("./assets/images/banner.bmp");
  background-position: center;
  background-size: cover;
}
</style>
