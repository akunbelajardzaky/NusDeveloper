<script setup>
  import Default from "./common/Default.vue"
</script>
<template>
  <html class="html dm_sans">
    <main class="layout bg-gray-200 dark:bg-[#14141f]">
      <header-import>
        <Default />
      </header-import>
    </main>
  </html>
</template>
<style scoped>
  @import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..set40,500;0,9..40,600;0,9..40,700;0,9..40,800;0,9..40,900;0,9..40,1000;1,9..40,300;1,9..40,400;1,9..40,500;1,9..40,600;1,9..40,700;1,9..40,800;1,9..40,900;1,9..40,1000&display=swap");
  .dm_sans {
    font-family: "DM Sans", sans-serif;
  }

  @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

  .Poppins {
    font-family: 'Poppins', sans-serif;
  }
</style>
