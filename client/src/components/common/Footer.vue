<template>
  <footer
    class="w-[95%] border-t-[1px] py-8 lg:w-[65%] mx-auto text-gray-500 text-sm"
  >
    <div class="flex flex-col text-center md:text-left md:flex-row gap-8">
      <div class="basis-2/6">
        <div class="font-bold text-xl mb-4 text-gray-800">
          <router-link
          :to="{ name: 'Home', params: {} }"
          class="flex items-center"
        >
          <span class="">Coffee Store</span>
        </router-link>
        </div>
        <div class="mb-20 md:mb-8">
         Mang đến cuộc sống cà phê tốt nhất kề từ năm 1996. Từ những người đam mê cà phê đến những người thực sự.
        </div>
        <div class="text-gray-400 hover:text-coffee-400">
          Coffee Store Inc. © 2024
        </div>
      </div>
      <div class="basis-1/6">
        <div class="uppercase font-semibold tracking-wider text-gray-600 mb-4">
          Menu
        </div>
        <div class="flex flex-col gap-3">
          <div>
          <router-link :to="{ name: 'Home', params: {} }">
            <span class="mx-2">Trang Chủ</span>
          </router-link>
          </div>
          <div>  <router-link :to="{ name: 'Product', params: {} }">
            <span class="mx-2">Sản phẩm</span></router-link>
          </div>

        <div>
          <router-link :to="{ name: 'About', params: {} }">
            <span class="mx-2">Về chúng tôi</span>
          </router-link>
        </div>
         
          <!-- <div><a href="#" class="hover:text-coffee-400">Style guild</a></div>
          <div><a href="#" class="hover:text-coffee-400">Herocode dev</a></div> -->
        </div>
      </div>
      <div class="basis-1/6">
        <div class="uppercase font-semibold tracking-wider text-gray-600 mb-4">
          Mạng xã hội
        </div>
        <div class="flex flex-col gap-3">
          <div><a href="#" class="hover:text-coffee-400">Facebook</a></div>
          <div><a href="#" class="hover:text-coffee-400">Instagram</a></div>
          <div><a href="#" class="hover:text-coffee-400">Pinterest</a></div>
          <div><a href="#" class="hover:text-coffee-400">Twitter</a></div>
        </div>
      </div>
      <div class="basis-2/6">
        <div class="uppercase font-semibold tracking-wider text-gray-600 mb-4">
          Liên hệ chúng tôi
        </div>
        <div class="flex flex-col gap-3">
          <div class="hover:text-coffee-400">Chúng tôi luôn sẵn sàng trợ giúp</div>
          <div class="mb-16">
            <a
              href="https://mail.google.com/mail/u/0/#inbox"
              class="hover:text-coffee-400 text-xl tracking-widest font-bold text-coffee-600"
              >Tinh-Salam-Binh@gmail.com</a
            >
          </div>
          <!-- <div>
            <a href="#" class="hover:text-coffee-400">Được cung cấp bởi webflow</a>
          </div> -->
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style></style>
