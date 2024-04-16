<template>
  <div class="story w-[95%] lg:w-[65%] mx-auto mb-12">
    <div class="flex flex-col lg:flex-row justify-center items-center gap-4">
      <div class="basis-1/2">
        <video
          autoplay
          muted
          loop
          class="w-full rounded-md object-cover max-h-[370px]"
        >
          <source src="../../assets/videos/cafe.mp4" type="video/mp4" />
        </video>
      </div>
      <div class="text-center lg:text-left basis-1/2 lg:pl-8">
        <div
          class="text-2xl font-medium mb-4 capitalize leading-10 tracking-wide"
        >
          Sản phẩm của chúng tôi được xử lý bằng công nghệ hiện đại.
        </div>
        <div class="text-gray-500 leading-7 mb-6">
          Thức uống tuyệt hảo dành cho những ai thích vị ngọt hoặc muốn sự kết hợp động đáo giữa các món trán miệng và đồ uống.
          <br />
          Đánh thức năng lượng mỗi ngày phù hợp với những ai mới bước vào thế giới cà phê hoặc nghiện cà phê nhưng người muốn khám phá thêm nhiều hương vị mới.
        </div>
        <div class="">
          <router-link :to="{ name: 'Home', params: {} }">
            <span
              href=""
              class="text-coffee-400 uppercase pb-2 hover:text-coffee-600 text-base relative after:bg-coffee-200 hover:after:bg-coffee-600 after:absolute after:w-full after:h-0.5 after:bottom-0 after:left-0 after:transition-all after:duration-700 after:ease-in-out"
            >
              Xem cách làm
            </span></router-link
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
