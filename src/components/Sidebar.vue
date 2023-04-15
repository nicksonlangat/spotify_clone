<template>
    <aside id="logo-sidebar" class="fixed top-0 bg-[#121212] left-0 z-40 w-96 h-screen pt-3 transition-transform -translate-x-full shadow-lg border-r border-[#121212] sm:translate-x-0" aria-label="Sidebar">
       <div class="h-full px-3 pb-4 overflow-y-auto bg-theme">
          <div class="flex gap-2">
             <svg viewBox="0 0 16 16" class="h-10 w-10 text-white" xmlns="http://www.w3.org/2000/svg">
                <path
                   d="M8 0a8 8 0 100 16A8 8 0 008 0zm3.903 11.532a.695.695 0 01-.947.267 8.299 8.299 0 00-3.237-1.02 8.318 8.318 0 00-3.384.351.696.696 0 01-.423-1.326 9.668 9.668 0 013.948-.409 9.703 9.703 0 013.777 1.19.697.697 0 01.266.947zm.958-2.429a.695.695 0 01-.938.295 10.87 10.87 0 00-3.944-1.177 10.828 10.828 0 00-4.127.367.695.695 0 11-.386-1.336 12.264 12.264 0 014.653-.415c1.566.159 3.062.606 4.447 1.327.34.178.473.598.295.939zm.346-2.022a.69.69 0 01-.31-.073 13.454 13.454 0 00-4.659-1.345 13.423 13.423 0 00-4.843.383.695.695 0 11-.359-1.344 14.85 14.85 0 015.343-.423c1.802.183 3.532.682 5.139 1.484a.695.695 0 01-.311 1.318z"
                   fill="currentColor"/>
             </svg>
             <h3 class=" font-Pacifico text-[26px] text-white font-bold mb-8">
                Spotify
             </h3>
          </div>
          <ul class="space-y-4 font-medium">
             <li>
                <a href="/" class="flex items-center p-2 text-white text-sm">
                   <svg viewBox="0 0 512 512" :width=size :height=size xmlns="http://www.w3.org/2000/svg">
                      <path
                         d="M 256.274 60.84 L 84.324 166.237 L 84.324 443.063 L 193.27 443.063 L 193.27 293.73 L 320.228 293.73 L 320.228 443.063 L 428.222 443.063 L 428.222 165.476 L 256.274 60.84 Z M 256.274 35.95 L 448.452 149.145 L 448.452 464.395 L 300 464.395 L 300 315.062 L 213.499 315.062 L 213.499 464.395 L 64.095 464.395 L 64.095 150.161 L 256.274 35.95 Z"
                         fill="currentColor"/>
                   </svg>
                   <span class="ml-3">Home</span>
                </a>
             </li>
             <li>
                <a href="/" class="flex items-center p-2 text-gray-400 hover:text-white text-sm">
                   <svg viewBox="0 0 512 512" :width=size :height=size xmlns="http://www.w3.org/2000/svg">
                      <path
                         d="M349.714 347.937l93.714 109.969-16.254 13.969-93.969-109.969q-48.508 36.825-109.207 36.825-36.826 0-70.476-14.349t-57.905-38.603-38.603-57.905-14.349-70.476 14.349-70.476 38.603-57.905 57.905-38.603 70.476-14.349 70.476 14.349 57.905 38.603 38.603 57.905 14.349 70.476q0 37.841-14.73 71.619t-40.889 58.921zM224 377.397q43.428 0 80.254-21.461t58.286-58.286 21.461-80.254-21.461-80.254-58.286-58.285-80.254-21.46-80.254 21.46-58.285 58.285-21.46 80.254 21.46 80.254 58.285 58.286 80.254 21.461z"
                         fill="currentColor" fillRule="evenodd"/>
                   </svg>
                   <span class="ml-3">Search</span>
                </a>
             </li>
             <li>
                <a href="/" class="flex items-center p-2 text-gray-400 hover:text-white text-sm">
                   <svg viewBox="0 0 512 512" :width=size :height=size xmlns="http://www.w3.org/2000/svg">
                      <path
                         d="M291.301 81.778l166.349 373.587-19.301 8.635-166.349-373.587zM64 463.746v-384h21.334v384h-21.334zM192 463.746v-384h21.334v384h-21.334z"
                         fill="currentColor"/>
                   </svg>
                   <span class="ml-3">Your Library</span>
                </a>
             </li>
             <li class="pb-4">
             </li>
             <li>
                <a href="/" class="flex items-center p-2 text-gray-400 hover:text-white text-sm">
                   <svg viewBox="0 0 16 16" :width=size :height=size xmlns="http://www.w3.org/2000/svg">
                      <path d="M14 7H9V2H7v5H2v2h5v5h2V9h5z" fill="currentColor"/>
                      <path fill="none" d="M0 0h16v16H0z"/>
                   </svg>
                   <span class="ml-3">Create Playlist</span>
                </a>
             </li>
             <li>
                <a href="/" class="flex items-center p-2 text-gray-400 hover:text-white text-sm">
                   <svg viewBox="0 0 16 16" :width=size :height=size xmlns="http://www.w3.org/2000/svg">
                      <path fill="none" d="M0 0h16v16H0z"/>
                      <path fill="currentColor"
                         d="M13.797 2.727a4.057 4.057 0 00-5.488-.253.558.558 0 01-.31.112.531.531 0 01-.311-.112 4.054 4.054 0 00-5.487.253c-.77.77-1.194 1.794-1.194 2.883s.424 2.113 1.168 2.855l4.462 5.223a1.791 1.791 0 002.726 0l4.435-5.195a4.052 4.052 0 001.195-2.883 4.057 4.057 0 00-1.196-2.883z"/>
                   </svg>
                   <span class="ml-3">Liked Songs</span>
                </a>
             </li>
             <hr class="h-px my-8 bg-gray-700 border-0">
             <li> <span class="ml-3 text-gray-400 hover:text-white text-sm">2023</span></li>
          </ul>
          <div class="mt-72">
             <div class="mt-64 text-gray-400 hover:text-white cursor-pointer gap-4 font-semibold flex justify-start">
                <svg viewBox="0 0 24 24" :width=size :height=size xmlns="http://www.w3.org/2000/svg">
                   <path fill="currentColor"
                      d="M11.5 0C5.149 0 0 5.148 0 11.5 0 17.851 5.149 23 11.5 23S23 17.851 23 11.5C23 5.148 17.851 0 11.5 0zm0 22C5.71 22 1 17.29 1 11.5S5.71 1 11.5 1 22 5.71 22 11.5 17.29 22 11.5 22zm.499-6.842V5h-1v10.149l-3.418-3.975-.758.652 4.678 5.44 4.694-5.439-.757-.653-3.439 3.984z"/>
                </svg>
                Install App
             </div>
          </div>
       </div>
    </aside>
</template>

<script>
export default {
        data() {
            return {
                isOpen: false,
                size: 22,
            }
        }
}
    
 </script>