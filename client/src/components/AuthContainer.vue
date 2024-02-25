<template>
  <section class="w-full bg-white">
    <div class="mx-auto max-w-7xl">
      <div class="flex flex-col lg:flex-row m-h-screen">
        <div
          class="relative w-full bg-cover lg:w-6/12 xl:w-7/12 bg-gradient-to-r from-white via-white to-gray-100"
        >
          <div
            class="relative flex flex-col items-center justify-center w-full h-full px-10 my-20 lg:px-16 lg:my-0"
          >
            <div class="flex flex-col items-start space-y-8 tracking-tight lg:max-w-3xl">
              <div class="relative">
                <p class="mb-2 font-medium text-gray-700 uppercase">Nơi xác nhận</p>
                <h2 class="text-5xl font-bold text-gray-900 xl:text-6xl">
                  Xác nhận văn bằng tín chỉ bằng blockchain
                </h2>
              </div>
              <p class="text-2xl text-gray-700">
                Một nền tảng mạnh mẽ nơi sinh viên, nhà trường và các nhà tuyển dụng có thể xác minh thông tin một cách an toàn,
                dễ dàng.
              </p>
              <router-link
                to="/"
                class="inline-block px-8 py-5 text-xl font-medium text-center text-white transition duration-200 bg-indigo-600 rounded-lg hover:bg-blue-700 ease"
                data-primary="blue-600"
                data-rounded="rounded-lg"
                >Learn more</router-link
              >
            </div>
          </div>
        </div>

        <slot />
      </div>
    </div>
  </section>
</template>
