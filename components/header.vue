<template>
<div>
  <div class="bg-slate-200 ">
    <div class="container flex justify-between mx-auto w-8/12">
      <ul class="flex py-1.5 text-blue-500">
        <li  class="flex justify-center justify-items-center text-sm">
          <nuxt-link to=""> <img src="~/assets/bosh_sahifa.png" class="inline mx-2" width="16%" />Bosh sahifa</nuxt-link>
        </li>
        <li class="flex text-sm">
          <nuxt-link to=""><img src="~/assets/phone.png" class="inline mx-2" width="8%" />mobile versiya</nuxt-link>
        </li>
      </ul>
      <div class="py-1.5 flex ">
        <span class="text-sm font-normal">Saytdagi oxirgi ma'lumot yangilangan sana: 29-март 2022, 20:37</span>
      </div>
    </div>
  </div>
  <div class="bg-slate-700 container-fluid ">
    <div class="container mx-auto w-8/12 py-6 flex">
      <div class="w-6/12">
        <img src="~/assets/logo.png" width="100%" />
      </div>
      <div class="flex w-6/12 justify-items-end">
        <div class="w-8/12 flex justify-end items-center">
          <form action="/">
            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" >
          </form>
        </div>
        <div class="w-4/12 flex justify-end items-center">
          <div class="w-3/12"></div>
            <div class="w-9/12">
              <span class="inline mx-2 text-green-400">0 371 209-97-02 </span>
              <span class="inline mx-2 text-green-400">Ishonch telefoni</span>
           </div>
          <svg class="w-6 h-6	text-indigo-500 text-white inline" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path></svg>
        </div>
      </div>
    </div>
  </div>
  <div id="navbar" class="container-fluid bg-green-500 py-1.5">
    <div class="container mx-auto w-8/12">

      <ul class="flex">
        <li class="w-2/12 text-white	 flex justify-center items-center"><nuxt-link to="/doniyor">menu</nuxt-link></li>
        <li class="w-2/12 text-white flex justify-center items-center"><nuxt-link to="/umidbek/">menu</nuxt-link></li>
        <li class="w-2/12 text-white flex justify-center items-center"><nuxt-link to="">menu</nuxt-link></li>
        <li class="w-2/12 text-white flex justify-center items-center"><nuxt-link to="">menu</nuxt-link></li>
        <li class="w-2/12 text-white flex justify-center items-center"><nuxt-link to="">menu</nuxt-link></li>
        <li class="w-2/12 text-white flex justify-center items-center"><nuxt-link to="">menu</nuxt-link></li>
      </ul>
    </div>
  </div>
</div>
</template>
<script src="https://cdn.jsdelivr.net/gh/alpinejs/alpine@v2.x.x/dist/alpine.min.js" defer></script>
<script>
export default {
  name: 'IndexPage'
}
</script>
