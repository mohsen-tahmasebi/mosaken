<template>
  <div
    class="bg-primary pb-10 mb-[10vh] text-green-50 flex flex-col items-center gap-5"
  >
    <div class="flex items-center flex-col lg:flex-row">
      <h1 class="text-8xl sm:px-14 py-20">مُصَکِنْ</h1>
      <p class="text-2xl">
        <span
          v-for="(word, index) in ['مدیریت', 'صنعت', 'کشاورزی', 'نوین']"
          :key="index"
        >
          <span class="text-white">{{ word.slice(0, 1) }}</span>
          <span class="text-white/80">{{ word.slice(1) + " " }}</span>
        </span>
      </p>
    </div>
    <div class="text-secondary my-6">
      <button
        class="p-2 text-xl px-6 rounded-md mx-2 transition-all duration-300 text-white bg-secondary border border-white shadow-md hover:scale-105"
      >
        شروع کنید
      </button>
      <button
        class="p-2 text-xl px-6 rounded-md mx-2 transition-all duration-300 bg-white border border-secondary shadow-md hover:scale-105"
      >
        خدمات
        <span class="animate-pulse duration-300 delay-500"> مُصَکِنْ </span>
      </button>
    </div>
  </div>

  <div>
    <div class="sec mb-[16vh] lg:mx-[5%] flex flex-col-reverse lg:flex-row justify-between">
      <div class="lg:w-1/2 mt-2 mx-6">
        <h2 class="text-2xl md:text-3xl my-6 text-secondary/80">
          مُصَکِنْ: بازنگرشی به کشاورزی
        </h2>
        <p class="text-justify">
          لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با
          استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در
          ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و
          کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی
          در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می
          طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی
          الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این
          صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و
          شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای
          اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده
          قرار گیرد.
        </p>
      </div>
      <img
        src="/images/neural.jpg"
        class="lg:rounded-md w-full lg:max-w-xl object-cover"
        alt="modern farming"
      />
    </div>
    <div class="sec mb-[16vh] lg:mx-[5%] flex flex-col-reverse lg:flex-row justify-between">
      <div class="lg:w-1/2 mt-2 mx-6">
        <h2 class="text-2xl md:text-3xl my-6 text-secondary/80">
          مُصَکِنْ: بازنگرشی به کشاورزی
        </h2>
        <p class="text-justify">
          لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با
          استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در
          ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و
          کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی
          در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می
          طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی
          الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این
          صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و
          شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای
          اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده
          قرار گیرد.
        </p>
      </div>
      <img
        src="/images/neural.jpg"
        class="lg:rounded-md w-full lg:max-w-xl object-cover"
        alt="modern farming"
      />
    </div>
    <div class="sec mb-[16vh] lg:mx-[5%] flex flex-col-reverse lg:flex-row justify-between">
      <div class="lg:w-1/2 mt-2 mx-6">
        <h2 class="text-2xl md:text-3xl my-6 text-secondary/80">
          مُصَکِنْ: بازنگرشی به کشاورزی
        </h2>
        <p class="text-justify">
          لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با
          استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در
          ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و
          کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی
          در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می
          طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی
          الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این
          صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و
          شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای
          اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده
          قرار گیرد.
        </p>
      </div>
      <img
        src="/images/neural.jpg"
        class="lg:rounded-md w-full lg:max-w-xl object-cover"
        alt="modern farming"
      />
    </div>
  </div>
</template>

