<template>
    <div>
        <app-header></app-header>
        <br>
        <app-form></app-form>
    </div>

</template>
<script>
  import Header from './components/Header.vue';
  import Form from './components/Form.vue';
  export default {
    components: {
      appHeader: Header,
      appForm: Form
    }
  }
</script>
<style>


</style>
