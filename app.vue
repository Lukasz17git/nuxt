<template>
   <div class="bg-slate-900 text-white w-screen h-screen">
      <header>
         <ul>
            <li class="flex items-center gap-2 p-4">
               <NuxtLink to="/">Home</NuxtLink>
               <NuxtLink to="/about">About</NuxtLink>
               <NuxtLink to="/events">Events</NuxtLink>
               <NuxtLink to="/events/123">Events 123</NuxtLink>
            </li>
         </ul>
      </header>
      <NuxtLayout>
         <NuxtPage />
      </NuxtLayout>
   </div>
</template>
