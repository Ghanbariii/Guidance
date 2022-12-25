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
      <div class="second-part__title px-8 lg:px-0 lg:pr-8 order-last">
        <p class="first-step__title font-medium text-base w-24 h-10 mt-5 pt-2 pr-6">
          گام دوم
        </p>
        <p class="second-step__subtitle font-light text-lg lg:text-xl mt-10">
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
      <div class="order-first mt-10">
        <img src="../assets/img/guides/rezerv-guide/2.png" alt="Reservation Order Price" class="order-price-image">
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
    <div class="third-part lg:flex lg:items-center xl:px-32 mt-20 lg:mt-52 px-2">
      <div class="third-part__title">
        <p class="first-step__title font-medium text-base mt-5 w-24 h-10 pt-2 pr-6">
          گام سوم
        </p>
        <div class="third-part__subtitle font-light">
          <p class="text-lg lg:text-2xl">
            با لمس آیکون
            <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="16" cy="16" r="16" fill="#3B5184" />
              <path
                d="M22.1175 13.6136H15.9398C15.4573 13.6136 15.0573 13.2024 15.0573 12.7064C15.0573 12.2105 15.4573 11.7993 15.9398 11.7993H22.1175C22.5999 11.7993 23 12.2105 23 12.7064C23 13.2024 22.6117 13.6136 22.1175 13.6136Z"
                fill="white" />
              <path
                d="M9.76211 14.5329C9.53854 14.5329 9.31496 14.4482 9.13846 14.2668L8.25593 13.3596C7.91469 13.0088 7.91469 12.4282 8.25593 12.0775C8.59718 11.7267 9.16199 11.7267 9.50324 12.0775L9.76211 12.3436L11.786 10.2631C12.1273 9.91231 12.6921 9.91231 13.0333 10.2631C13.3746 10.6139 13.3746 11.1945 13.0333 11.5452L10.3858 14.2668C10.221 14.4361 9.99745 14.5329 9.76211 14.5329Z"
                fill="white" />
              <path
                d="M22.1175 22.0807H15.9398C15.4573 22.0807 15.0573 21.6695 15.0573 21.1735C15.0573 20.6776 15.4573 20.2663 15.9398 20.2663H22.1175C22.5999 20.2663 23 20.6776 23 21.1735C23 21.6695 22.6117 22.0807 22.1175 22.0807Z"
                fill="white" />
              <path
                d="M9.76211 23C9.53854 23 9.31496 22.9153 9.13846 22.7339L8.25593 21.8267C7.91469 21.4759 7.91469 20.8953 8.25593 20.5445C8.59718 20.1938 9.16199 20.1938 9.50324 20.5445L9.76211 20.8107L11.786 18.7302C12.1273 18.3794 12.6921 18.3794 13.0333 18.7302C13.3746 19.081 13.3746 19.6615 13.0333 20.0123L10.3858 22.7339C10.221 22.9032 9.99745 23 9.76211 23Z"
                fill="white" />
            </svg>

            در صفحات سفارشات روزء امکان مشاهده و مدیریت سفارشات رزرو شده را خواهید دید.
          </p>
        </div>
        <div class="first-step__warning flex mt-10 font-regular text-md md:text-lg">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
            stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M12 9v3.75m-9.303 3.376c-.866 1.5.217 3.374 1.948 3.374h14.71c1.73 0 2.813-1.874 1.948-3.374L13.949 3.378c-.866-1.5-3.032-1.5-3.898 0L2.697 16.126zM12 15.75h.007v.008H12v-.008z" />
          </svg>
          <p class="pr-4">
            بارهایی که قبلا رزرو شده اند، امکان رزرو مجدد را نخواهند داشت.
          </p>
        </div>
      </div>
      <div class="third-part__image mt-20 lg:mt-2">
        <img src="../assets/img/guides/rezerv-guide/3.png" alt="">
      </div>
    </div>
    <div class="third-part__arrow_part hidden xl:block">
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
    <div class="fourth-part lg:flex  xl:px-32 mt-20 lg:mt-44 px-2">
      <div class="fourth-part__part pr-0 lg:pr-12 mt-16 order-last">
        <p class="first-step__title font-medium text-base mt-5 w-24 h-10 pt-2 pr-4 mr-8">
          گام چهارم
        </p>
        <div class="fourth-part__subtitle mt-4">
          <p class="font-light text-lg lg:text-2xl">
            در این صفحه ، سفارشات رزرو شده را به ترتیب مشاهده خواهید کرد. اولین سفارشی که در لیست سفارشات رزرو شده، نوبت
            شما باشد به شما اختصاص می یابد.
          </p>
        </div>
        <div class="fourth-part__Check flex mt-8">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
            stroke="currentColor" class="w-8 h-8 block">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M9 12.75L11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 01-1.043 3.296 3.745 3.745 0 01-3.296 1.043A3.745 3.745 0 0112 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 01-3.296-1.043 3.745 3.745 0 01-1.043-3.296A3.745 3.745 0 013 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 011.043-3.296 3.746 3.746 0 013.296-1.043A3.746 3.746 0 0112 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 013.296 1.043 3.746 3.746 0 011.043 3.296A3.745 3.745 0 0121 12z" />
          </svg>
          <p class="font-regular text-base lg:text-lg xl:text-xl items-center px-2 text-center lg:text-justify">
            سفارشی که به شما اختصاص یابد به رنگ سبز نمایش داده خواهد شد.
          </p>
        </div>
        <div class="fourth-part__warning flex font-regular mt-5 mr-1">
          <svg style="width:24px;height:24px" viewBox="0 0 24 24">
            <path fill="currentColor" d="M12,2L1,21H23M12,6L19.53,19H4.47M11,10V14H13V10M11,16V18H13V16" />
          </svg>
          <p class="pr-4 text-base lg:text-lg xl:text-xl flex">
            در صورت انصراف از رزرو سفارش ، آیکون
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" class="mx-2" xmlns="http://www.w3.org/2000/svg">
              <g clip-path="url(#clip0_978_2954)">
                <path
                  d="M16 9V19H8V9H16ZM14.5 3H9.5L8.5 4H5V6H19V4H15.5L14.5 3ZM18 7H6V19C6 20.1 6.9 21 8 21H16C17.1 21 18 20.1 18 19V7Z"
                  fill="#FF4949" />
              </g>
              <defs>
                <clipPath id="clip0_978_2954">
                  <rect width="24" height="24" fill="white" />
                </clipPath>
              </defs>
            </svg>
            را لمس نمایید
          </p>
        </div>
        <div class="fourth-part__warning_2 flex items-center font-regular mt-5 mr-1">
          <svg style="width:54px;height:54px" viewBox="0 0 24 24">
            <path fill="currentColor" d="M12,2L1,21H23M12,6L19.53,19H4.47M11,10V14H13V10M11,16V18H13V16" />
          </svg>
          <p class="pr-4 text-base lg:text-lg xl:text-xl leading-loose">
            درصورتیکه “صدور نوبت بعدی هنگام تخصیص سفارش “ را در وضعیت فعال قرار دهید ، با تخصیص سفارش به شما ، نوبت به
            صورت خودکار صادر خواهد شد.
          </p>
        </div>
      </div>
      <div class="fourth-part__image order-first mt-10">
        <img src="../assets/img/guides/rezerv-guide/4.png" class="">
      </div>
    </div>
    <div class="fifth-part lg:flex xl:px-32 mt-20 lg:mt-32 px-2 flex items-center">
      <div class="fifth-part__subtitle">
        <div>
          <span class="font-medium text-md lg:text-2xl block">
            توجه داشته باشید
          </span>
        </div>
        <p class=" font-light text-md lg:text-xl">
          که با لمس آیکون
            <img src="../assets/img/guides/account-icon.png">
          در هر سفارش ، صفحه روبرو باز خواهد شد که در آن امکان مشاهده راننده های آن سفارش راخواهید داشت.
        </p>
      </div>
      <img src="../assets/img/guides/rezerv-guide/4_2.png">
    </div>
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
    margin-left: auto !important;
    margin-right: auto !important;
  }

  .third-part__image {
    width: 372px !important;
    height: 374px !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }

  .fourth-part__image {
    width: 436px !important;
    height: auto !important;
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

  .arrow_part {
    width: 377px !important;
    height: 150px !important;
    left: 100px !important;
  }

  .order-price-image {
    width: 400px !important;
    height: 415px !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }

  .third-part__image {
    width: 452px !important;
    height: 454px !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }

  .fourth-part__image {
    width: 436px !important;
    height: auto !important;
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
  width: 1966px;
  height: auto;
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

.third-part__subtitle {
  color: #666666;
}

.third-part__image {
  width: 896px;
  height: auto;
}

.third-part__arrow_part {
  position: absolute;
  top: 3000px;
  left: 300px;
}

.fourth-part__image {
  width: 1266px;
  height: auto;
}

.fourth-part__subtitle {
  color: #666666;

}

.fourth-part__subtitle p {
  line-height: 40px;
}

.fourth-part__Check {
  color: #198B39;
}

.fourth-part__warning_2 svg {
  width: 60x;
  height: 60px;
}

.fourth-part__warning,
.fourth-part__warning_2 {
  color: #EB3627;
}

.fourth-part__warning p,
.fourth-part__warning_2 p {
  line-height: 30px;
}
.fifth-part__subtitle span{
  color: #3B5184;
}
</style>
<script>
export default {
  name: 'IndexPage'
}
</script>
