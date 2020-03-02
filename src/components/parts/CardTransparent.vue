<template>
  <div class="w-full lg:w-3/12 px-4 text-center">
    <div
      class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
    >
      <i :class="'fas fa-'+icon+' text-xl'"></i>
    </div>
    <h6 class="text-xl mt-5 font-semibold text-white">{{title}}</h6>
    <p
      class="mt-2 mb-4 text-gray-500"
    >{{description}}</p>
  </div>
</template>

<script>
export default {
 props: ['title', 'description', 'icon']
}</script>
