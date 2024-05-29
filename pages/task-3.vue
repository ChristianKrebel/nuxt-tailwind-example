<template>
  <div>
    <h1 class="text-4xl pb-2 text-primary">Task 3</h1>
    <p class="pb-10">Help:
      <NuxtLink class="d-link" external target="_blank" to="https://tailwindcss.com/docs/hover-focus-and-other-states#styling-based-on-parent-state">
        https://tailwindcss.com/docs/hover-focus-and-other-states#styling-based-on-parent-state
      </NuxtLink>
    </p>

    <!-- Start: Add your code here -->
    <div class="d-card w-96 bg-base-100 shadow-xl group/example">
      <div class="d-card-body">
        <h2 class="d-card-title">Daisy Card title!</h2>
        <p>I want to be colored differently when hovered over the card (group).</p>
        <div class="d-card-actions justify-end">
          <button class="d-btn d-btn-primary">Click me</button>
        </div>
      </div>
    </div>
    <!-- End: Add your code here -->

  </div>
</template>
