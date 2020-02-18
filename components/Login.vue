<template>
  <div class="login flex items-center w-auto font-sans">
    <form class="w-1/3 text-left mr-32 ml-24" action="">
      <div class="flex items-center">
        <img src="~/assets/image/brand.svg" alt="" />
        <h1 class="text-indigo-800 text-lg ml-2 mt-2 font-extrabold italic">
          Gas Report
        </h1>
      </div>
      <div class="mt-10">
        <h1 class="text-indigo-800 font-semibold text-2xl">
          Sign In To Gas Report
        </h1>
        <p class="mt-2 text-xs text-gray-500">
          Untuk masuk ke sistem, silahkan masukkan email dan user password Anda
        </p>
      </div>
      <div class="text-indigo-800 mt-8">
        <label for="">EMAIL</label>
        <input
          class="mt-2 w-full pl-5 py-2 h-10 bg-gray-200 rounded-sm	"
          type="text"
          placeholder="Ex:mail@mail.com"
        />
      </div>
      <div class="text-indigo-800 mt-4">
        <label for="">PASSWORD</label>
        <input
          class="mt-2 w-full pl-5 py-2 h-10 bg-gray-200 rounded-sm	"
          type="text"
          placeholder="Password"
        />
      </div>
      <div class="mt-8">
        <button class="bg-indigo-800 w-full py-3 px-4 rounded text-white">
          Sig In
        </button>
      </div>
      <div class="mt-4">
        <input class="mr-3 leading-tight" type="checkbox" />
        <span class="text-sm">
          Tetap masuk
        </span>
      </div>
    </form>
    <div class="w-2/3 h-screen w-full ">
      <div class="text-white absolute items-center">
        <h1 class="">PT. Energasindo Heksa Karya</h1>
        <h3>Your Business Partner for Energy Solution</h3>
      </div>
      <img class="h-full w-full" src="~/assets/image/login.jpg" alt="" />
    </div>
  </div>
</template>
<style></style>
