<script setup></script>

<template>
  <nav class="flex justify-around">
    <div class="logo mt-5">
      <h1 class="">موضات</h1>
    </div>
    <div class="nav-images mt-5 flex justify-between">
      <img src="/src/assets/person.svg" width="20" height="20" class="inline ml-5" />
      <img src="/src/assets/cart.svg" width="20" height="20" class="inline ml-5" />
      <img src="/src/assets/bag.svg" width="20" height="20" class="inline ml-5" />
    </div>
  </nav>
  <header class="mt-20 flex justify-around">
    <div class="card-one">
      <h1 class="mb-9 font-bold text-3xl">ملابس صيفية / شتوية</h1>
      <p class="font-light w-[350px]">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod debitis deleniti libero sunt
        unde aut eaque repellendus.
      </p>
      <img src="/src/assets/image1forBranding.png" class="w-[300px] mt-8" />
    </div>
    <div class="card-tow">
      <img src="/src/assets/image2forBranding.png" class="w-[300px] mb-8 rounded-t-[40rem]" />
      <p class="font-light w-[350px] mb-9">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod debitis deleniti libero sunt
        unde aut eaque repellendus.
      </p>
      <BUtton class="border border-[#Af7452] text-[#Af7452] py-2 px-5">تصفح</BUtton>
    </div>
  </header>

  <section class="flex pt-20 justify-around">
    <div class="flex flex-col justify-around items-start">
      <h1 class="mb-9 font-bold text-3xl">
        ملابس رسمية <br />
        شعبية
      </h1>
      <p class="w-[340px] mb-5 font-light">
        Quod debitis deleniti libero sunt unde aut eaque repellendus.
      </p>
      <BUtton class="border border-[#Af7452] text-[#Af7452] py-2 px-5">تسوق الان</BUtton>
    </div>
    <img src="/src/assets/image1forBranding.png" class="w-[300px] mb-8" />
  </section>

  <section class="flex justify-center items-center mt-20 p-10">
    <div class="p-10 ml-10">
      <h1 class="font-bold mb-6">اشتري الان وادفع لاحقا</h1>
      <p class="font-thin w-[14erm]">يمكنك الشراء والتحقق من جودة المنتج لمدة تصل الى 30 يوما.</p>
      <BUtton class="border border-[#Af7452] text-[#Af7452] mt-5 py-2 px-5">تسوق الان</BUtton>
    </div>
    <div class="p-10 ml-10">
      <h1 class="font-bold mb-6">نقاط ولاء نقدا</h1>
      <p class="font-thin w-[14erm]">
        يمكنك تجميع نقاطك عبر طلباتك الخاصة او رابط الاحالة الخاص بك.
      </p>
      <BUtton class="border border-[#Af7452] text-[#Af7452] mt-5 py-2 px-5">تسوق الان</BUtton>
    </div>
    <div class="p-10 ml-10">
      <h1 class="font-bold mb-6">طرق دفع امنه</h1>
      <p class="font-thin w-[14erm]">تستطيع الدفع بطرق 100% امنه سوا في التطبيق او على موقعنا.</p>
      <BUtton class="border border-[#Af7452] text-[#Af7452] mt-5 py-2 px-5">تسوق الان</BUtton>
    </div>
  </section>
</template>

<style scoped></style>
