<template>
  <b-form-group class="pt-lg-0 pt-3">
    <div>
      <span class="mr-1">Made with</span>
      <img src="@/assets/logo.png" :width="18" class="mr-1" alt="Vuejs" title="Vuejs" />
      <span>by </span>
      <b-link target="_blank" href="https://github.com/alexchristianqr">@alexchristianqr </b-link>
      <span>with love </span>
      <span class="text-danger" style="font-size: 18px">&hearts;</span>
    </div>
  </b-form-group>
</template>

<script>
export default {
  name: 'MyFooter',
}
</script>

<style scoped></style>
