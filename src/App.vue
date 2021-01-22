<template>
  <div class="bg-gray-100 text-white text-sm">
    <div class="h-16 bg-green-900 flex items-center justify-center border-b">

      <div class="w-full flex items-center max-w-screen-lg">
        <div class="w-10">
          <svg xmlns='http://www.w3.org/2000/svg' fill="currentColor" class='ionicon text-green-500' viewBox='0 0 512 512'><title>Logo</title><path d='M480 173.59c0-104.13-68.26-134.65-68.26-134.65C377.3 23.15 318.2 16.5 256.8 16h-1.51c-61.4.5-120.46 7.15-154.88 22.94 0 0-68.27 30.52-68.27 134.65 0 23.85-.46 52.35.29 82.59C34.91 358 51.11 458.37 145.32 483.29c43.43 11.49 80.73 13.89 110.76 12.24 54.47-3 85-19.42 85-19.42l-1.79-39.5s-38.93 12.27-82.64 10.77c-43.31-1.48-89-4.67-96-57.81a108.44 108.44 0 01-1-14.9 558.91 558.91 0 0096.39 12.85c32.95 1.51 63.84-1.93 95.22-5.67 60.18-7.18 112.58-44.24 119.16-78.09 10.42-53.34 9.58-130.17 9.58-130.17zm-80.54 134.16h-50V185.38c0-25.8-10.86-38.89-32.58-38.89-24 0-36.06 15.53-36.06 46.24v67h-49.66v-67c0-30.71-12-46.24-36.06-46.24-21.72 0-32.58 13.09-32.58 38.89v122.37h-50V181.67q0-38.65 19.75-61.39c13.6-15.15 31.4-22.92 53.51-22.92 25.58 0 44.95 9.82 57.75 29.48L256 147.69l12.45-20.85c12.81-19.66 32.17-29.48 57.75-29.48 22.11 0 39.91 7.77 53.51 22.92q19.79 22.72 19.75 61.39z'/></svg>
        </div>
        <div class="ml-auto hidden">
          <button
                  class="px-3  py-1 hover:bg-gray-100 focus:outline-none focus:shadow-md bg-white text-gray-700 text-xs capitalize rounded-sm" >view all</button></div>
      </div>
    </div>
    <div class="flex w-full items-center justify-center ">
      <div class="mt-8 w-full h-full text-gray-700 max-w-screen-lg">
        <div class="flex items-center">
          <div class="my-2 ml-auto flex items-center relative">
            <div class="fill-current text-gray-300 w-5 absolute left-2">
              <svg xmlns='http://www.w3.org/2000/svg' class='ionicon' viewBox='0 0 512 512'><title>Search</title><path d='M221.09 64a157.09 157.09 0 10157.09 157.09A157.1 157.1 0 00221.09 64z' fill='none' stroke='currentColor' stroke-miterlimit='10' stroke-width='32'/><path fill='none' stroke='currentColor' stroke-linecap='round' stroke-miterlimit='10' stroke-width='32' d='M338.29 338.29L448 448'/></svg>
            </div>
            <label>
              <input  class="capitalize border p-2 placeholder-gray-300 pl-8 focus:outline-none focus:shadow rounded-sm" type="text" placeholder="enter patient name">
            </label>
          </div>
          <div class="ml-4 flex items-center relative">
            <select class="bg-gray-200 border border-green-600 text-gray-700 appearance-none capitalize p-2 border focus:outline-none focus:shadow rounded-sm pr-9" >
              <option class="">filter by</option>
              <option>hello</option>
              <option>hello</option>
              <option>hello</option>
            </select>
            <div class="w-6 absolute right-2">
              <svg xmlns='http://www.w3.org/2000/svg' class='ionicon fill-current text-green-700' viewBox='0 0 512 512'><title>Filter</title><path fill='none' stroke='currentColor' stroke-linecap='round' stroke-linejoin='round' stroke-width='32' d='M32 144h448M112 256h288M208 368h96'/></svg>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script >
</script>


<style>
</style>
