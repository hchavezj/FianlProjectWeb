<template>
  <div class="card max-w-[80%] m-auto">
    <p class="font-funk text-[40px]">Contact Information</p>
    <table class="table-auto m-auto w-[400px] border-separate border-spacing-4">
      <tr>
        <td class="text-right">Address:</td>
        <td class="text-left">123 Main St<br />Mission, TX, 78572</td>
      </tr>
      <tr>
        <td class="text-right">Phone:</td>
        <td class="text-left">123-456-1111</td>
      </tr>
      <tr>
        <td class="text-right">Fax:</td>
        <td class="text-left">123-456-2222</td>
      </tr>
      <tr>
        <td class="text-right">Email:</td>
        <td class="text-left">name@example.com</td>
      </tr>
    </table>
  </div>
</template>

<style scoped>
.card {
  background: #fff;
  margin: 0 auto 100px;
  padding: 45px;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}
</style>

<script>
// @ is an alias to /src

export default {
  name: "ContactView",
  components: {},
};
</script>
