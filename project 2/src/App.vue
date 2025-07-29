<template>
  <nav>
    <ul class="flex mt-6">
      <li><a href="" class="ml-[5rem] text-[#1BC8D3] border-b-2 pb-2">Home</a></li>
      <li><a href="" class="ml-10 hover:text-[#1BC8D3] hover:border-b-2 hover:pb-2">Skills</a></li>
      <li>
        <a href="" class="ml-10 hover:text-[#1BC8D3] hover:border-b-2 hover:pb-2">Services</a>
      </li>
      <li><a href="" class="ml-10 hover:text-[#1BC8D3] hover:border-b-2 hover:pb-2">Work</a></li>
    </ul>
  </nav>
  <header class="hero flex lg:flex-row md:flex-col sm:flex-col justify-between items-center mt-18">
    <div>
      <img src="./assets/images/hero.jpg" />
    </div>
    <div class="mr-10 ml-10 sm:mt-[6rem]">
      <h1 class="text-5xl font-bold mb-10">Web<span class="text-[#1BC8D3]"> Agency</span></h1>
      <p class="w-96 mb-10">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure amet eius natus eum nostrum
        harum illum dignissimos!
      </p>
      <div class="btns-container">
        <button class="bg-[#1BC8D3] text-white py-2 px-10 mr-5 mb-5">Services</button>
        <button class="border-b-2 border-black font-bold p-2 ml-6 mb-5">Learn More</button>
      </div>
      <div class="flex justify-around sm:flex-col md:flex-row mb-20">
        <div class="flex flex-col justify-center items-center p-2 mr-5 mt-5 bg-[#1BC8D3]">
          <h1 class="mt-5"><span class="font-bold">5 Star</span> Experience</h1>
          <p class="text-center w-60 p-2">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam nulla ad labore nam.
          </p>
        </div>
        <div
          class="flex flex-col justify-center items-center p-2 mr-5 mt-5 bg-[#1BC8D3] opacity-60"
        >
          <h1 class="mt-5">Make<span class="font-bold"> Your</span> Offer</h1>
          <p class="text-center w-60 p-2">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam nulla ad labore nam.
          </p>
        </div>
      </div>
    </div>
  </header>
  <section
    class="mt-[10rem] ml-[5rem] flex justify-around items-center md:flex-row sm:flex-col md:text-left sm:text-center"
  >
    <div>
      <h1 class="text-5xl font-bold mb-10">
        OUR <br />
        <span class="text-[#1BC8D3]"> Skills</span>
      </h1>
      <p class="w-96 mb-10">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic officiis tenetur aliquam id
        incidunt?
      </p>
      <button class="bg-[#1BC8D3] text-white py-2 px-10 mr-5 mb-5">Services</button>
    </div>
    <div class="image"><img src="./assets/images/section-two.jpg" class="w-[500px]" /></div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped></style>
