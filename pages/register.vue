<template>
  <form
    class="max-w-lg p-4 px-8 h-3/4 sm:my-6 mx-auto sm:border border-primary/40 rounded-md flex flex-col items-start"
    @submit.prevent="() => {}"
  >
    <label for="name" class="w-full">
      <label for="name">نام و نام خانوادگی</label>
      <input
        type="text"
        id="name"
        class="w-full border border-gray-500 rounded-sm my-2 p-2 px-4 block"
      />
    </label>
    <label for="melli" class="w-full">
      <label for="melli">کد ملی</label>
      <input
        type="text"
        id="melli"
        class="w-full border border-gray-500 rounded-sm my-2 p-2 px-4 block"
      />
    </label>
    <label for="mobile" class="w-full">
      <label for="mobile">شماره موبایل</label>
      <input
        type="text"
        id="mobile"
        class="w-full border border-gray-500 rounded-sm my-2 p-2 px-4 block"
      />
    </label>
    <label for="area" class="w-full">
      <label class="" for="area">متراژ</label>
      <div class="flex items-center">
        <input
          type="number"
          id="area"
          class="w-full border border-gray-500 rounded-sm rounded-l-none my-2 p-2 px-4"
          min="0"
        />
        <label
          for="area"
          class="p-2 px-4 border border-r-0 rounded-sm rounded-r-none border-gray-500"
          >کیلومتر</label
        >
      </div>
    </label>

    <label class="w-full" for="address">
      <label for="address">نشانی</label>
      <textarea
        id="address"
        rows="2"
        class="w-full border border-gray-500 rounded-sm my-2 p-2 px-4 block"
      ></textarea>
    </label>

    <label class="w-full" for="description">
      <label for="description">توضیحات</label>
      <textarea
        id="description"
        rows="5"
        class="w-full border border-gray-500 rounded-sm my-2 p-2 px-4 block"
      ></textarea>
    </label>

    <button class="w-full rounded-md bg-primary p-3 text-xl text-white border">ثبت</button>
  </form>
</template>

<style>
input,textarea,button{
  outline: none;
}

input:focus, textarea:focus, button:focus{
  @apply border-black;

}
</style>
