<script setup lang="ts">
const year = new Date().getFullYear()
</script>

<template>
  <footer class="p-4 bg-green-800 w-full text-white">
    <di class="mx-w-screen-xl mx-auto flex flex-wrap gap-4 justify-center items-center">
      <p>
        &copy; {{ year }}
        Tocaku Impact Tracker. All Rights Reserved
      </p>
      <p>
        Developed By:
        <a href="https://github.com/tocaku" target="_blank" class="text-blue-300 text-lg"
          >Tocaku
        </a>
      </p>
      <a href="https://github.com/tocaku" target="_blank" class="">
        <i class="pi pi-github"> Source Code</i>
      </a>
    </di>
  </footer>
</template>
