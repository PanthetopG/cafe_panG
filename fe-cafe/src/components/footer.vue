<template>
  <div>
    <footer class="footer">
      <div class="d-sm-flex justify-content-center justify-content-sm-between">
        <span class="float-none float-sm-right d-block mt-1 mt-sm-0 text-center"
          > {{ currentYear }}</span
        >
      </div>
    </footer>
  </div>
</template>

<script>
export default {
    name: 'App',
    data(){
      return{
        currentYear: new Date().getFullYear()
      }
    }
};
</script>

<style></style>
