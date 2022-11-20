<template>
  <div class="mb-2">
    <img
      class="object-cover max-h-[1200px]"
      src="../assets/FlowerBanner.png"
      alt="none"
    />
  </div>
  <p class="card pb-2 mb-2">
    About the page, I Would have information about what they would do and
    services are provided here.
  </p>
  <div class="columns card">
    <p class="font-bold font-funk text-[2.5rem]">Header</p>
    <p class="font-bold font-funk text-[2.5rem]">Header</p>
    <p class="p-2">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quibusdam
      incidunt dignissimos atque nemo voluptates possimus perspiciatis ab beatae
      accusantium totam voluptate commodi, praesentium, corrupti inventore,
      quidem minima saepe minus eveniet.
    </p>
    <p class="p-2">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quibusdam
      incidunt dignissimos atque nemo voluptates possimus perspiciatis ab beatae
      accusantium totam voluptate commodi, praesentium, corrupti inventore,
      quidem minima saepe minus eveniet.
    </p>
    <p class="font-bold font-funk text-[2.5rem]">Header</p>
    <p class="font-bold font-funk text-[2.5rem]">Header</p>
    <p class="p-2">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quibusdam
      incidunt dignissimos atque nemo voluptates possimus perspiciatis ab beatae
      accusantium totam voluptate commodi, praesentium, corrupti inventore,
      quidem minima saepe minus eveniet. Lorem ipsum dolor sit amet consectetur
      adipisicing elit. Omnis porro doloribus consectetur. Nostrum quae
      molestias, error totam minima neque dolore. Nostrum repellendus ipsam iste
      laudantium. Harum non ratione voluptate dolore.
    </p>
    <p class="p-2">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quibusdam
      incidunt dignissimos atque nemo voluptates possimus perspiciatis ab beatae
      accusantium totam voluptate commodi, praesentium, corrupti inventore,
      quidem minima saepe minus eveniet. Lorem ipsum dolor sit amet consectetur
      adipisicing elit. Omnis porro doloribus consectetur. Nostrum quae
      molestias, error totam minima neque dolore. Nostrum repellendus ipsam iste
      laudantium. Harum non ratione voluptate dolore.
    </p>
  </div>
</template>

<style scoped>
img {
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}

.column {
  column-rule: 2px solid rgba(0, 0, 0, 0.2);
}
.columns {
  display: grid;
  gap: 1.5rem;
  grid-template-columns: repeat(2, 1fr);
  padding-block: 2rem;
  margin-inline: auto;
}
</style>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {},
};
</script>
