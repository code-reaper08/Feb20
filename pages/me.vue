<template>
  <div class="flexer bg-black">
    <div class="masonry">
      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322273-e909ae9f-92a8-4d87-9c8f-745f10b28ab2.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322317-b3212277-8ee4-4389-a708-b15fd14a20f1.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322328-331672a1-c28d-4dab-8837-cca88671e2fc.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322333-4a6c8717-e558-44ee-80aa-ceddd0cddf7b.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322345-3aa02305-ac30-421a-9dc6-3ff7a7239669.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322351-c66fad2f-0089-4c02-a829-e464919ee6aa.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322362-0ac2c608-730a-4bcf-a31d-241026c31193.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322372-0748a559-1c0c-4dd1-8e78-7ff250fe2973.jpg"
        />
      </div>
      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322385-b2b679dd-963d-438f-aeb1-fc05b5aad391.jpg"
        />
      </div>

      <div class="mItem">
        <img
          src="https://user-images.githubusercontent.com/64256342/154322390-659cb2c8-a3d1-4b97-bb08-9a4fe4724e61.jpg"
        />
      </div>
    </div>
    <div class="flex justify-center pb-10">
      <NuxtLink to="/">
        <p class="text-white cursor-pointer">← Back to Home</p>
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.flexer {
  background-image: url("https://64.media.tumblr.com/b29afc099269a74c0a2c0169545327bd/tumblr_ndv49dBypR1qjmwryo1_400.gif");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
img {
  width: 100%;
  filter: grayscale(100);
}
img:hover {
  filter: grayscale(0);
  transition: ease-in-out 0.5s;
}
.masonry {
  /*column-count: 4;*/
  column-count: 4;
  column-gap: 16px;
}

.masonry .mItem {
  display: inline-block;
  margin-bottom: 16px;
  width: 100%;
}

@media (max-width: 1199px) {
  .masonry {
    column-count: 3;
  }
}

@media (max-width: 991px) {
  .masonry {
    column-count: 2;
  }
}

@media (max-width: 767px) {
  .masonry {
    column-count: 1;
  }
}
</style>
