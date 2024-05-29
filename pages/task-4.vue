<template>
  <div>
    <h1 class="text-4xl pb-2 text-primary">Task 4</h1>
    <p class="pb-10">Help:
      <NuxtLink class="d-link" external target="_blank" to="https://tailwindcss.com/docs/functions-and-directives#apply">
        https://tailwindcss.com/docs/functions-and-directives#apply
      </NuxtLink>
    </p>

    <!-- Start: Add your code here -->
    <div class="d-card w-[400px] bg-base-100 shadow-xl example">
      <div class="d-card-body">
        <h2 class="d-card-title">Daisy Card title!</h2>
        <p>Convert my pure CSS rules to Tailwind utility classes in the class "example".</p>
        <label class="d-input d-input-bordered flex items-center gap-2">
          <input class="grow" placeholder="Search" type="text" />
          <kbd class="d-kbd d-kbd-sm">⌘</kbd>
          <kbd class="d-kbd d-kbd-sm">K</kbd>
        </label>
      </div>
    </div>
    <!-- End: Add your code here -->

  </div>
</template>

<style scoped>
.example {
  /* Use @apply here */
  background-color: #fee2e2; /* bg-red-100 */
  rotate: 6deg;
  height: 300px;
}
</style>
