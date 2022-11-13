<template>
  <div class="container max-w-[80%] m-auto">
    <div class="card">
      <div class="flex">
        <img src="../assets/profile.jpg" alt="none" class="h-32" />
        <table class="table-auto border-separate border-spacing-x-2">
          <tr>
            <td class="text-left">Name:</td>
            <td class="text-left">Jane Smith</td>
          </tr>
          <tr>
            <td class="text-right">Education:</td>
            <td class="text-left">MBA from Fake College</td>
          </tr>
        </table>
      </div>
      <p class="text-left pt-4">
        My Name is Jane. I graduated from some college and. Lorem ipsum dolor
        sit, amet consectetur adipisicing elit. Id facilis sit quae ipsa
        laboriosam possimus dolores numquam nesciunt excepturi eos, corrupti
        impedit quibusdam quo distinctio nemo voluptatibus nisi! Recusandae,
        porro!
      </p>
    </div>
  </div>
</template>

<style scoped>
.card {
  background: #fff;
  margin: 0 auto 100px;
  padding: 45px;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}

img {
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.1), 0 5px 5px 0 rgba(0, 0, 0, 0.14);
  filter: drop-shadow(0 0 0.8rem rgb(45, 54, 71));
}
</style>
