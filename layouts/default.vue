<template>
  <header>
    <div class="d-navbar bg-base-100">
      <div class="flex-1">
        <NuxtLink class="d-btn d-btn-ghost text-xl" to="/">Nuxt + Tailwind + daisyUI</NuxtLink>
      </div>
      <div class="flex-none">
        <ul class="d-menu d-menu-horizontal px-1">
          <li><NuxtLink to="/task-1">Task 1</NuxtLink></li>
          <li><NuxtLink to="/task-2">Task 2</NuxtLink></li>
          <li><NuxtLink to="/task-3">Task 3</NuxtLink></li>
          <li><NuxtLink to="/task-4">Task 4</NuxtLink></li>
        </ul>
      </div>
    </div>
  </header>
  <main>
    <div class="pt-20 px-4 flex justify-center min-h-screen">
      <slot />
    </div>
  </main>
  <footer class="footer footer-center p-4 bg-base-200 text-base-content">
    <aside>
      <p>© 2024</p>
    </aside>
  </footer>
</template>
