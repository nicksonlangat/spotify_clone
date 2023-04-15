<template>
  <div>
     <Sidebar />
     <div class="p-4 sm:ml-96">
        <div>
           <div class="flex justify-between">
              <div class="flex text-white gap-4">
                 <span class="rounded-full bg-[#121212] px-1 py-1 cursor-pointer">
                    <svg viewBox="0 0 24 24" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <polyline stroke="currentColor" points="16 4 7 12 16 20" fill="none"/>
                    </svg>
                 </span>
                 <span class="rounded-full bg-[#121212] px-1 py-1 cursor-pointer">
                    <svg viewBox="0 0 24 24" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <polyline stroke="currentColor" points="8 4 17 12 8 20" fill="none"/>
                    </svg>
                 </span>
              </div>
              <button class="bg-[#121212] text-white rounded-full px-4 py-0.5">
                 <div class="flex justify-between gap-2">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mt-0.5">
                       <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z" />
                    </svg>
                    <span>f9trssfshjnbvv543</span>
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                       <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
                    </svg>
                 </div>
              </button>
           </div>
           <div class="mt-8">
              <h3 class="text-white font-bold text-4xl">Good evening</h3>
           </div>
           <div class="mt-8 grid grid-cols-3 gap-x-8 gap-y-6">
              <div class="flex bg-[#121212] hover:bg-[#363737] rounded">
                 <div class="w-1/3">
                    <img class="object-cover rounded-l h-20 w-20" src="../assets/davido.webp" alt="">
                 </div>
                 <div class="w-2/3 mt-6">
                    <h3 class="text-white text-xl font-bold">Davido</h3>
                 </div>
              </div>
              <div class="flex bg-[#121212] hover:bg-[#363737] rounded">
                 <div class="w-1/3">
                    <img class="object-cover rounded-l h-20 w-20" src="../assets/Mavado.webp" alt="">
                 </div>
                 <div class="w-2/3 mt-6">
                    <h3 class="text-white text-xl font-bold">Mavado</h3>
                 </div>
              </div>
              <div class="flex bg-[#121212] hover:bg-[#363737] rounded">
                 <div class="w-1/3">
                    <img class="object-cover rounded-l h-20 w-20" src="../assets/magix.webp" alt="">
                 </div>
                 <div class="w-2/3 mt-6">
                    <h3 class="text-white text-xl font-bold">Magixx</h3>
                 </div>
              </div>
              <div class="flex bg-[#121212] hover:bg-[#363737] rounded">
                 <div class="w-1/3">
                    <img class="object-cover rounded-l h-20 w-20" src="../assets/Chris_Brown_5,_2012.jpeg" alt="">
                 </div>
                 <div class="w-2/3 mt-6">
                    <h3 class="text-white text-xl font-bold">Chris Brown</h3>
                 </div>
              </div>
              <div class="flex bg-[#121212] hover:bg-[#363737] rounded">
                 <div class="w-1/3">
                    <img class="object-cover rounded-l h-20 w-20" src="../assets/burna.png" alt="">
                 </div>
                 <div class="w-2/3 mt-6">
                    <h3 class="text-white text-xl font-bold">Burna Boy</h3>
                 </div>
              </div>
              <div class="flex bg-[#121212] hover:bg-[#363737] rounded">
                 <div class="w-1/3">
                    <img class="object-cover rounded-l h-20 w-20" src="../assets/mimi.jpeg" alt="">
                 </div>
                 <div class="w-2/3 mt-6">
                    <h3 class="text-white text-xl font-bold">Mimi Mars</h3>
                 </div>
              </div>
           </div>
           <div class="mt-8">
              <h3 class="text-white font-semibold text-2xl">Jump back in</h3>
           </div>
           <div class="grid grid-cols-4 gap-x-6 mt-6">
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded px-4" src="../assets/animal.webp" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">Animal Instinct Riddim</h3>
                    <p class="text-gray-400 text-sm">Various Artists</p>
                 </div>
              </div>
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded-lg px-4" src="../assets/ruby.jpeg" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">Ruby</h3>
                    <p class="text-gray-400 text-sm">Artist</p>
                 </div>
              </div>
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded-lg px-4" src="../assets/YKB-Picture.jpeg" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">YKB</h3>
                    <p class="text-gray-400 text-sm">Artist</p>
                 </div>
              </div>
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded-lg px-4" src="../assets/wande_coal.jpeg" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">Wande Coal</h3>
                    <p class="text-gray-400 text-sm">Artist</p>
                 </div>
              </div>
           </div>
           <div class="mt-8">
              <h3 class="text-white font-semibold text-2xl">Made for you</h3>
           </div>
           <div class="grid grid-cols-4 gap-x-6 mt-6 pb-32">
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded-lg px-4" src="../assets/Iyanya-One-Side-Artwork.jpeg" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">One side</h3>
                    <p class="text-gray-400 text-sm">Song</p>
                 </div>
              </div>
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded-lg px-4" src="../assets/love.webp" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">Love don't cost...</h3>
                    <p class="text-gray-400 text-sm">Song</p>
                 </div>
              </div>
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded-lg px-4" src="../assets/Omah-Lay-Soso-1000x1000.jpeg" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">Soso</h3>
                    <p class="text-gray-400 text-sm">Song</p>
                 </div>
              </div>
              <div class="hover:bg-[#121212] bg-[#292929] rounded-lg">
                 <img class="pt-4 rounded-lg px-4" src="../assets/Victony-profile.jpeg" alt="">
                 <div class="ml-6 mt-2 pb-4">
                    <h3 class="text-white font-semibold">Victony</h3>
                    <p class="text-gray-400 text-sm">Artist</p>
                 </div>
              </div>
           </div>
           <footer class="fixed bottom-0 left-96 z-20 w-full p-4 hover:bg-[#121212] bg-[#292929] border-t border-gray-200 shadow md:flex md:items-center md:justify-between md:p-6">
              <div class="flex justify-between">
                 <div class="flex gap-2 text-white">
                    <img class="h-10 w-10" src="../assets/loyal.jpeg" alt="">
                    <div class="flex mb-2 flex-col">
                       <p>Loyal</p>
                       <p class="text-xs">Magixx</p>
                    </div>
                 </div>
                 <div class="flex text-white font-bold gap-6 ml-72 items-center justify-center">
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path
                          d="M4.5 6.8l.7-.8C4.1 4.7 2.5 4 .9 4v1c1.3 0 2.6.6 3.5 1.6l.1.2zm7.5 4.7c-1.2 0-2.3-.5-3.2-1.3l-.6.8c1 1 2.4 1.5 3.8 1.5V14l3.5-2-3.5-2v1.5zm0-6V7l3.5-2L12 3v1.5c-1.6 0-3.2.7-4.2 2l-3.4 3.9c-.9 1-2.2 1.6-3.5 1.6v1c1.6 0 3.2-.7 4.2-2l3.4-3.9c.9-1 2.2-1.6 3.5-1.6z"
                          fill="currentColor"/>
                    </svg>
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path d="M13 2.5L5 7.119V3H3v10h2V8.881l8 4.619z" fill="currentColor"/>
                    </svg>
                    <span class="bg-white text-black rounded-full px-1 py-1">
                       <svg viewBox="0 0 24 24" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                          <polygon points="21.57 12 5.98 3 5.98 21 21.57 12" fill="currentColor"/>
                       </svg>
                    </span>
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path d="M11 3v4.119L3 2.5v11l8-4.619V13h2V3z" fill="currentColor"/>
                    </svg>
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path
                          d="M5.5 5H10v1.5l3.5-2-3.5-2V4H5.5C3 4 1 6 1 8.5c0 .6.1 1.2.4 1.8l.9-.5C2.1 9.4 2 9 2 8.5 2 6.6 3.6 5 5.5 5zm9.1 1.7l-.9.5c.2.4.3.8.3 1.3 0 1.9-1.6 3.5-3.5 3.5H6v-1.5l-3.5 2 3.5 2V13h4.5C13 13 15 11 15 8.5c0-.6-.1-1.2-.4-1.8z"
                          fill="currentColor"/>
                    </svg>
                 </div>
                 <div class="flex text-white font-bold gap-4 ml-72 items-center justify-center">
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path
                          d="M8.5 1A4.505 4.505 0 004 5.5c0 .731.191 1.411.502 2.022L1.99 13.163a1.307 1.307 0 00.541 1.666l.605.349a1.307 1.307 0 001.649-.283L9.009 9.95C11.248 9.692 13 7.807 13 5.5 13 3.019 10.981 1 8.5 1zM4.023 14.245a.307.307 0 01-.388.066l-.605-.349a.309.309 0 01-.128-.393l2.26-5.078A4.476 4.476 0 007.715 9.92l-3.692 4.325zM8.5 9C6.57 9 5 7.43 5 5.5S6.57 2 8.5 2 12 3.57 12 5.5 10.429 9 8.5 9z"
                          fill="currentColor"/>
                    </svg>
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path d="M2 2v5l4.33-2.5L2 2zm0 12h14v-1H2v1zm0-4h14V9H2v1zm7-5v1h7V5H9z" fill="currentColor"/>
                    </svg>
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path
                          d="M0 3v8c0 .55.45 1 1 1h5v-1H1V3h5V2H1c-.55 0-1 .45-1 1zm3 11.5c0 .275.225.5.5.5H6v-1H3.5c-.275 0-.5.225-.5.5zM15 2H9c-.55 0-1 .45-1 1v11c0 .55.45 1 1 1h6c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 12H9V3h6v11zm-3-8a.75.75 0 100-1.5.75.75 0 000 1.5zm0 6a2 2 0 100-4 2 2 0 000 4zm0-3c.551 0 1 .449 1 1s-.449 1-1 1-1-.449-1-1 .449-1 1-1z"
                          fill="currentColor"/>
                    </svg>
                    <svg viewBox="0 0 16 16" width=22 height=22 xmlns="http://www.w3.org/2000/svg">
                       <path
                          d="M0 11.032v-6h2.802l5.198-3v12l-5.198-3H0zm7 1.27v-8.54l-3.929 2.27H1v4h2.071L7 12.302zm4.464-2.314q.401-.925.401-1.956 0-1.032-.4-1.957-.402-.924-1.124-1.623L11 3.69q.873.834 1.369 1.957.496 1.123.496 2.385 0 1.262-.496 2.385-.496 1.123-1.369 1.956l-.659-.762q.722-.698 1.123-1.623z"
                          fill="currentColor"/>
                    </svg>
                 </div>
              </div>
           </footer>
        </div>
     </div>
  </div>
</template>

<script>
import Sidebar from '@/components/Sidebar.vue';

export default {
  name: 'HomeView',
  components: {
   Sidebar
  }
}
</script>
