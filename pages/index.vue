<template>
  <div class="animate__animated animate__fadeIn">
    <Navigation />
    <div class="header">
      <div class="header__banner md:block absolute hidden">
        <img src="../assets/img/guides/header.jpeg" alt="Banner-Carvann" class="w-auto h-auto">
      </div>
      <div class="header__title flex justify-center">
        <p class="font-bold text-4xl items-center md:text-white mt-8 md:mt-12 lg:mt-20 xl:mt-24">
          آموزش <span class="text-5xl"> رزرو بار</span> در اپلیکیشن کاروان
        </p>
      </div>
      <div class="header__subtitle flex justify-center mt-8 text-2xl">
        <p class="md:text-white font-light">
          سفارشات مورد نظر را غیر حضوری رزرو کنید و از تخصیص آن مطمئن شوید.
        </p>
      </div>
    </div>
    <div class="section__first xl:mt-36 lg:px-4 xl:px-28 px-12 md:px-32 flex">
      <div class="lg:grid grid-rows-1 grid-flow-col gap-2 lg:pt-16 font-medium text-base">
        <div class="row-span-3">
          <p class="first-step__title w-24 h-10 mt-32 pt-2 pr-6">
            گام اول
          </p>
          <div class=" first-step__subtitle mt-8 xl:w-full">
            <p class="font-light leading-loose">
              برای رزرو بار ابتدا وارد صفحه سفارشات روز شوید. <br />
              برای هر سفارش امکان رزرو بار وجود دارد که با لمس دکمه<span> “رزرو سفارش” </span>میتوانید سفارش مورد نظر را
              رزرو کنید.

            </p>
          </div>
          <div class="first-step__warning flex mt-10 font-regular text-md md:text-lg">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M12 9v3.75m-9.303 3.376c-.866 1.5.217 3.374 1.948 3.374h14.71c1.73 0 2.813-1.874 1.948-3.374L13.949 3.378c-.866-1.5-3.032-1.5-3.898 0L2.697 16.126zM12 15.75h.007v.008H12v-.008z" />
            </svg>
            <p class="pr-4">
              برای رزرو بار ، دسترسی به لوکیشن الزامیست.
            </p>
          </div>
        </div>
        <div class="first-step__image mt-16">
          <img src="../assets/img/guides/rezerv-guide/1.png" alt="Guide Banner Number one">
        </div>
      </div>

    </div>
    <div class="first-step__part2 lg:px-16 xl:px-44 lg:flex">
      <img src="../assets/img/guides/rezerv-guide/1_2.jpg" alt="Reservetion Guide">
      <div class="flex justify-center lg:items-end leading-loose">
        <p class="font-light text-lg lg:text-xl px-20 md:px-32 lg:px-20 pt-10 text-justify xl:px-0 sm:leading-loose justify-center">
          <span class="font-medium text-xl lg:text-2xl ">توجه داشته باشید</span> <br />
          که بعد از لمس دکمه رزرو سفارش ، پیغامی دریافت میکنید<br /> که در آن امکان <span class="font-medium">انتخاب
            زمان بارگیری سفارش</span> را خواهید
          داشت
          ، با لمس گزینه سایر امکان وارد کردن تعداد روزهای مورد نظر را خواهید داشت.
        </p>
      </div>
    </div>
    <div class="arrow_part hidden lg:block">
      <svg width="777" height="250" viewBox="0 0 884 357" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M29.9714 36.7819L29.9712 131.615C29.9712 150.948 45.6443 166.622 64.976 166.622L811.455 166.622C830.786 166.622 846.46 182.297 846.46 201.63L846.46 356.782"
          stroke="#5D6569" stroke-dasharray="10 10" />
        <path
          d="M414 165.486C415.333 166.256 415.333 168.18 414 168.95L396 179.342C394.667 180.112 393 179.15 393 177.61L393 156.825C393 155.286 394.667 154.324 396 155.093L414 165.486Z"
          fill="#B8C4DF" />
        <path
          d="M456.5 163.62C458.5 164.774 458.5 167.661 456.5 168.816L435.5 180.94C433.5 182.095 431 180.652 431 178.342L431 154.093C431 151.784 433.5 150.341 435.5 151.495L456.5 163.62Z"
          fill="#3B5184" />
        <path
          d="M493 165.486C494.333 166.256 494.333 168.18 493 168.95L478 177.61C476.667 178.38 475 177.418 475 175.878L475 158.558C475 157.018 476.667 156.056 478 156.825L493 165.486Z"
          fill="#B8C4DF" />
      </svg>
    </div>
  </div>
</template>

<style>
@import '@/assets/css/fonts.css';

.body{
  animation :animate__slideInDown;
}


@media (max-width: 768px) {
  .header__title p {
    color: #24A973;
    font-size: 22px;
  }

  .header__subtitle p {
    padding: 0 24px;
    font-size: 14px;
    font-family: "medium";
  }

  .first-step__image {
    width: 436px !important;
    height: 420px !important;
  }

  .first-step__subtitle span {
    color: #3B5184;
    font-family: medium;
  }
  .first-step__part2 img {
  width: 362px !important;
  height: 364px !important;
  margin-left: auto !important;
  margin-right: auto !important;
}
}

@media (max-width: 1024px) {
  .first-step__part2 img {
  width: 362px !important;
  height: 364px !important;
  margin-left: auto !important;
  margin-right: auto !important;
}
}


.header__banner {
  z-index: -100 !important;
  top: 500;
}

.first-step__title {
  background-color: #E6FAF2;
  color: #27B97E;
  border-radius: 50px;
}

.first-step__image {
  width: 576px;
  height: 560px;
}

.first-step__subtitle p {
  color: #4B5155 !important;
  font-size: 22px !important;
}

.first-step__subtitle span {
  color: #3B5184;
  font-family: medium;
}

.first-step__warning {
  color: #EB3627;

}

.first-step__part2 p {
  color: #4B5155
}

.first-step__part2 span {
  color: #3B5184;
}

.first-step__part2 img {
  width: 324px;
  height: 322px;
}
.arrow_part svg{
  position: absolute;
  left:300px;
}
</style>
<script>
export default {
  name: 'IndexPage'
}
</script>
