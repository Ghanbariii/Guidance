<template>
  <div class="animate__animated animate__fadeIn">
    <Navigation />
    <div class="header">
      <div class="header__banner md:block absolute hidden">
        <img src="../assets/img/guides/header.jpeg" alt="Banner-Carvann" class="w-auto h-auto">
      </div>
      <div class="header__title flex justify-center">
        <p
          class="font-bold text-4xl items-center md:text-white mt-8 md:mt-12 lg:mt-20 xl:mt-24 animate__animated animate__fadeInDown">
          آموزش <span class="text-5xl"> رزرو بار</span> در اپلیکیشن کاروان
        </p>
      </div>
      <div class="header__subtitle flex justify-center mt-8 text-2xl">
        <p class="md:text-white font-light animate__animated animate__bounceInLeft">
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
    <div class="first-step__part2 lg:px-16 xl:px-40 lg:flex">
      <img src="../assets/img/guides/rezerv-guide/1_2.jpg" alt="Reservetion Guide">
      <div class="flex justify-center lg:items-end leading-loose">
        <p
          class="font-light text-lg lg:text-xl px-20 md:px-32 lg:px-20 pt-10 text-justify xl:px-0 sm:leading-loose justify-center">
          <span class="font-medium text-xl lg:text-2xl ">توجه داشته باشید</span> <br />
          که بعد از لمس دکمه رزرو سفارش ، پیغامی دریافت میکنید<br /> که در آن امکان <span class="font-medium">انتخاب
            زمان بارگیری سفارش</span> را خواهید
          داشت
          ، با لمس گزینه سایر امکان وارد کردن تعداد روزهای مورد نظر را خواهید داشت.
        </p>
      </div>
    </div>
    <div class="arrow_part hidden xl:block">
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
    <div class="second-step mt-20 lg:mt-64 xl:px-32 block lg:flex">
      <img src="../assets/img/guides/rezerv-guide/2.png" alt="Reservation Order Price" class="order-price-image">
      <div class="second-part__title pr-8">
        <p class="first-step__title font-medium text-base w-24 h-10 mt-5 pt-2 pr-6">
          گام دوم
        </p>
        <p class="second-step__subtitle font-light text-lg lg:text-xl mt-10 ">
          برای رزرو بار ملزم به پرداخت هزینه می باشید که در این مرحله با لمس دکمه <span> “پرداخت هزینه” </span>از موجودی
          کیف پول
          کاروان شما کسر و سفارش مورد نظر رزرو خواهد شد.
        </p>
        <img src="../assets/img/guides/rezerv-guide/warning.png" class="mt-6 warning-walet">
        <p class="second-step__lastItem font-light text-lg lg:text-xl mt-5">
          <span class="font-medium text-lg xl:text-2xl "> توجه داشته باشید</span> <br />
          درصورتیکه موجودی کیف پول، کافی نباشد پیغام بالا را در صفحه مشاهده خواهید کرد و امکان رزرو بار را نخواهید داشت.
          با لمس گزینه<span class="font-medium"> “افزایش موجودی”</span> امکان شارژ کیف پول کاروان فراهم می شود.
        </p>
        <div class="second-step__finaly flex mt-4">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
            stroke="currentColor" class="w-12 h-12">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M9 12.75L11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 01-1.043 3.296 3.745 3.745 0 01-3.296 1.043A3.745 3.745 0 0112 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 01-3.296-1.043 3.745 3.745 0 01-1.043-3.296A3.745 3.745 0 013 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 011.043-3.296 3.746 3.746 0 013.296-1.043A3.746 3.746 0 0112 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 013.296 1.043 3.746 3.746 0 011.043 3.296A3.745 3.745 0 0121 12z" />
          </svg>
          <p class="font-regular text-md lg:text-lg items-center px-2 text-center lg:text-justify">
            تا زمانیکه سفارش به شما اختصاص داده نشود ، نیازی به پرداخت هزینه مجدد نمی باشد و امکان رزرو سفارش برای شما
            وجود دارد.
          </p>
        </div>
      </div>
    </div>
    <div class="arrow-next-step-2 hidden xl:block">
      <svg width="777" height="250" viewBox="0 0 884 357" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M854.029 36.7819L854.029 131.615C854.029 150.948 838.356 166.622 819.024 166.622L72.5451 166.622C53.2135 166.622 37.5403 182.297 37.5403 201.63L37.5403 356.782"
          stroke="#5D6569" stroke-dasharray="10 10" />
        <path
          d="M470 165.486C468.667 166.256 468.667 168.18 470 168.95L488 179.342C489.333 180.112 491 179.15 491 177.61L491 156.825C491 155.286 489.333 154.324 488 155.093L470 165.486Z"
          fill="#B8C4DF" />
        <path
          d="M427.5 163.62C425.5 164.774 425.5 167.661 427.5 168.816L448.5 180.94C450.5 182.095 453 180.652 453 178.342L453 154.093C453 151.784 450.5 150.341 448.5 151.495L427.5 163.62Z"
          fill="#3B5184" />
        <path
          d="M391 165.486C389.667 166.256 389.667 168.18 391 168.95L406 177.61C407.333 178.38 409 177.418 409 175.878L409 158.558C409 157.018 407.333 156.056 406 156.825L391 165.486Z"
          fill="#B8C4DF" />
      </svg>
    </div>
    <div class="third-part lg:flex xl:px-32">
      <div class="items-center">
        <p class="first-step__title font-medium text-basemt-5 w-24 h-10">
          گام سوم
        </p>
        <p class="flex font-light text-lg lg:text-xl">
          با لمس ایکون
          <img src="../assets/img/guides/icon.svg" class="flex">
          در صفحه سفارشات روز، امکان مشاهده و مدیریت سفارشات رزرو شده را خواهید داشت.
        </p>
      </div>
    </div>
      <div class="first-step__warning flex mt-3 font-regular text-md md:text-lg xl:px-32">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
          class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round"
            d="M12 9v3.75m-9.303 3.376c-.866 1.5.217 3.374 1.948 3.374h14.71c1.73 0 2.813-1.874 1.948-3.374L13.949 3.378c-.866-1.5-3.032-1.5-3.898 0L2.697 16.126zM12 15.75h.007v.008H12v-.008z" />
        </svg>
        <p class="pr-4">
          بارهایی که قبلا رزرو شده اند، امکان رزرو مجدد را نخواهند داشت.
        </p>
      </div>
      <img src="../assets/img/guides/rezerv-guide/3.png" alt="">
  </div>
</template>

<style>
@import '@/assets/css/fonts.css';

.body {
  animation: animate__slideInDown;
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

  .order-price-image {
    width: 400px !important;
    height: 415px !important;
    margin-right: auto !important;
    margin-left: auto !important;
  }


}

@media (max-width: 1024px) {
  .first-step__part2 img {
    width: 362px !important;
    height: 364px !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }

  .arrow_part {
    width: 377px !important;
    height: 150px !important;
    left: 100px !important;
  }

  .order-price-image {
    width: 450px !important;
    height: 465px !important;
    margin-right: auto !important;
    margin-left: auto !important;
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

.first-step__subtitle span,
.second-step__subtitle span {
  color: #3B5184;
  font-family: medium;
}

.first-step__warning {
  color: #EB3627;

}

.first-step__part2 p,
.second-step__subtitle {
  color: #4B5155;
  line-height: 35px;
}

.first-step__part2 span {
  color: #3B5184;
}

.first-step__part2 img {
  width: 324px;
  height: 322px;
}

.arrow_part svg {
  position: absolute;
  left: 300px;
}

.order-price-image {
  width: 566px;
  height: 575px;
}

.warning-walet {
  width: 280px;
  height: 60.31px;
}

.second-step__lastItem {
  color: #4B5155;
  line-height: 35px;
}

.second-step__lastItem span {
  color: #3B5184;
}

.second-step__finaly {
  color: #198B39;

}

.order-last {
  order: 10000 !important;
}

.order-first {
  order: -1000 !important;
}

.arrow-next-step-2 {
  position: absolute;
  right: 300px;
}
</style>
<script>
export default {
  name: 'IndexPage'
}
</script>
