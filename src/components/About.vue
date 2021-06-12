<template>
  <div class="grid grid-cols-12 justify-between my-28" id="about">
    <h1
      class="
        col-span-12
        text-3xl
        md:text-5xl
        text-center
        mb-10
        color-green
        font-semibold
      "
    >
      About
    </h1>
    <div class="col-span-12 md:col-span-6 flex justify-center">
      <img src="@/assets/kautsar.png" alt="Kautsar" class="box" />
    </div>
    <div class="col-span-12 md:col-span-6 flex justify-center mt-8 md:mt-0">
      <iframe
        src="https://drive.google.com/file/d/1oZ1UKsM8tkrPIGR1zvnj0rzF7It8iORA/preview"
        class="frame w-full"
      ></iframe>
    </div>
  </div>
</template>

<style scoped>
.box {
  background-color: #4eb18d;
  border-radius: 56px;
}

.frame {
  height: 400px;
}

@media (min-width: 768px) {
  .frame {
    height: 100%;
  }
}
</style>