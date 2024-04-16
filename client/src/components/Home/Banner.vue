<template>
  <div
    class="banner slide h-[530px] bg-banner-bg bg-cover bg-no-repeat bg-bottom mb-12"
  >
    <div
      class="w-full h-full flex justify-center items-center bg-gray-900 bg-opacity-60"
    >
      <div class="mx-16 text-white text-center">
        <div class="uppercase mb-6">Chào Mừng Đến Với Cửa Hàng Chúng Tôi</div>
        <div class="font-medium text-5xl mb-6 uppercase">Coffee Store</div>
        <div class="mb-6">
          
          Chúng tôi mang đến cho bạn Những Ly Coffee đặc biệt để giúp bạn Tỉnh Táo và Sáng Tạo
        </div>
        <div class="font-medium flex justify-center">
          <router-link :to="{ name: 'Product', params: {} }">
            <div
              class="bg-white w-max rounded-sm text-gray-900 px-8 py-4 tracking-wider text-xs uppercase cursor-pointer hover:opacity-90"
            >
             Khám phá sản phẩm
            </div>
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.banner {
  background-image: url("@/assets/images/slider-bg.jpg");
}
</style>
