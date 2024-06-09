<script setup lang="ts"></script>

<template>
  <div class="w-screen flex justify-center">
    <div class="w-9/12 query-builder justify-center grid grid-rows-1 grid-cols-1 p-2">
      <textarea
        ref="queryInput"
        placeholder="Enter your query here..."
        class="h-40 p-2 resize-y rounded-md dark:bg-slate-800 dark:text-white outline focus:outline-none focus:ring focus:outline-cyan-500 transition-all duration-75"
      ></textarea>
      <button
        class="h-12 w-28 outline hover:outline-offset-2 hover:outline-cyan-500 dark:text-white rounded-md p-2 justify-self-end mt-4 dark:bg-slate-800 transition-all duration-75"
        type="button"
      >
        Run Query
      </button>
    </div>
  </div>
</template>
