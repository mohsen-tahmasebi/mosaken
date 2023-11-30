<template>
    <form
      class="max-w-lg p-4 px-8 h-3/4 sm:my-6 mx-auto sm:border border-primary/40 rounded-md flex flex-col items-start"
      @submit.prevent="() => $router.push('/dashboard')"
    >

      <label for="melli" class="w-full">
        <label for="melli">کد ملی</label>
        <input
          type="text"
          id="melli"
          class="w-full border border-gray-500 rounded-sm my-2 p-2 px-4 block"
        />
      </label>
      <label for="pw" class="w-full">
        <label for="pw">رمز عبور</label>
        <input
          type="password"
          id="pw"
          class="w-full border border-gray-500 rounded-sm my-2 p-2 px-4 block"
        />
      </label>

  
      <button class="w-full rounded-md bg-primary p-3 text-xl text-white border">ورود</button>
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
  