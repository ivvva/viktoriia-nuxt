<template>
  <div>
    <div v-if="$mq === 'desktop'">
      <nav class="w-[100vw] top-0 left-0 fixed z-10 flex h-9 m-3 justify-around align-center h-11 p-11 text-xl text-white font-UncutSansMedium">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/works">Works</NuxtLink>
        <NuxtLink to="/contact">Contact</NuxtLink>
      </nav>
    </div>
    <div v-else>
      <nav class="w-100 top-0 left-0 fixed z-10 flex h-9 m-3 ">
        <button class="text-white font-semibold ml-[18rem] right-0 md:ml-12 md:text-2xl md:mt-8 sm:ml-10">MENU</button>
      </nav>
    </div>
  </header>

    <Nuxt />
  </div>
</template>
