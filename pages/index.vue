<template>
  <div class="w-full px-2 mx-auto overflow-hidden sm:px-10 xxxl:overflow-visible smd:px-2 lg:px-6 xl:px-4 xxl:px-0 max-w-7xl font-Inter">
    <header class="flex items-center justify-between w-full my-6 text-sm lg:text-base ">
      <div class="">
        <svg
          width="142"
          height="56"
          viewBox="0 0 142 56"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <circle cx="28" cy="28" r="28" fill="#FF8227" />
          <path
            d="M36.75 19.25V37.625H31.1153V30.4619H25.7597V37.625H20.125V19.25H25.7597V25.8681H31.1153V19.25H36.75Z"
            fill="white"
          />
          <path
            d="M75.904 38V18.4H79.488V26.548H88.28V18.4H91.864V38H88.28V29.46H79.488V38H75.904ZM102.254 38.336C100.91 38.336 99.6962 38.028 98.6135 37.412C97.5495 36.796 96.7002 35.9467 96.0655 34.864C95.4495 33.7627 95.1415 32.4933 95.1415 31.056C95.1415 29.6187 95.4589 28.3587 96.0935 27.276C96.7282 26.1747 97.5775 25.316 98.6415 24.7C99.7242 24.084 100.938 23.776 102.282 23.776C103.607 23.776 104.802 24.084 105.866 24.7C106.948 25.316 107.798 26.1747 108.414 27.276C109.048 28.3587 109.366 29.6187 109.366 31.056C109.366 32.4933 109.048 33.7627 108.414 34.864C107.798 35.9467 106.948 36.796 105.866 37.412C104.783 38.028 103.579 38.336 102.254 38.336ZM102.254 35.228C103.187 35.228 103.999 34.8827 104.69 34.192C105.38 33.4827 105.726 32.4373 105.726 31.056C105.726 29.6747 105.38 28.6387 104.69 27.948C103.999 27.2387 103.196 26.884 102.282 26.884C101.33 26.884 100.508 27.2387 99.8175 27.948C99.1455 28.6387 98.8095 29.6747 98.8095 31.056C98.8095 32.4373 99.1455 33.4827 99.8175 34.192C100.508 34.8827 101.32 35.228 102.254 35.228ZM112.57 38V24.112H115.734L116.014 26.464C116.443 25.6427 117.059 24.9893 117.862 24.504C118.683 24.0187 119.645 23.776 120.746 23.776C122.463 23.776 123.798 24.3173 124.75 25.4C125.702 26.4827 126.178 28.0693 126.178 30.16V38H122.594V30.496C122.594 29.3013 122.351 28.3867 121.866 27.752C121.381 27.1173 120.625 26.8 119.598 26.8C118.59 26.8 117.759 27.1547 117.106 27.864C116.471 28.5733 116.154 29.5627 116.154 30.832V38H112.57ZM128.709 38V35.116L135.793 27.08H128.793V24.112H139.881V26.996L132.685 35.032H140.021V38H128.709Z"
            fill="black"
          />
        </svg>
      </div>

      <div class="justify-between hidden w-full max-w-xs smd:flex lg:max-w-md xl:max-w-lg">
        <div class="p-2 lg:px-4 xl:p-4 xl:px-8 i">
          Buy
        </div>
        <div class="p-2 lg:px-4 xl:p-4 xl:px-8">
          Sell
        </div>
        <div class="flex items-center p-2 lg:px-4 xl:p-4 xl:px-8">
          <div class="">
            Agents
          </div>
          <div class="">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M8 11C7.87213 11 7.74413 10.9511 7.6465 10.8535L2.6465 5.85347C2.45113 5.6581 2.45113 5.34172 2.6465 5.14647C2.84188 4.95122 3.15825 4.9511 3.3535 5.14647L8 9.79298L12.6465 5.14647C12.8419 4.9511 13.1583 4.9511 13.3535 5.14647C13.5488 5.34185 13.5489 5.65822 13.3535 5.85347L8.3535 10.8535C8.25588 10.9511 8.12788 11 8 11Z"
                fill="#3F4149"
              />
            </svg>
          </div>
        </div>
        <div class="p-2 lg:px-4 xl:p-4 xl:px-8">
          Contact
        </div>
      </div>
      <div class="flex items-center">
        <div class="hidden mr-12 md:flex ">
          Login
        </div>
        <div
          class="items-center hidden px-4 py-2 text-white rounded-full xs:flex sm:py-3 sm:px-8 bg-orange"
        >
          <div class="">
            <svg
              width="27"
              height="24"
              viewBox="0 0 27 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect width="26.4466" height="24" rx="12" fill="#FF8227" />
              <path
                d="M13.2233 11.25C10.8122 11.25 8.49986 12.1192 6.79496 13.6664C5.09006 15.2135 4.13226 17.312 4.13226 19.5V21C4.13226 21.5967 4.39348 22.169 4.85845 22.591C5.32343 23.0129 5.95406 23.25 6.61163 23.25H19.8349C20.4925 23.25 21.1231 23.0129 21.5881 22.591C22.0531 22.169 22.3143 21.5967 22.3143 21V19.5C22.3143 17.312 21.3565 15.2135 19.6516 13.6664C17.9467 12.1192 15.6344 11.25 13.2233 11.25Z"
                fill="white"
              />
              <path
                d="M13.2233 9.75C15.962 9.75 18.1821 7.73528 18.1821 5.25C18.1821 2.76472 15.962 0.75 13.2233 0.75C10.4847 0.75 8.26459 2.76472 8.26459 5.25C8.26459 7.73528 10.4847 9.75 13.2233 9.75Z"
                fill="white"
              />
            </svg>
          </div>
          Create Account
        </div>
      </div>
    </header>

    <div class="grid h-full md:grid-cols-2 place-items-center xl:place-items-start xxxl:place-items-center" >
      <div class="space-y-8 lg:-ml-12 lg:space-y-12 xxl:space-y-8 xxxl:space-y-12 xl:ml-0">
        <div class="inline p-2 px-8 rounded-full sm:px-12 bg-orange-trans text-orange">
          A new way to find properties
        </div>
        <div
          class="text-4xl font-bold leading-tight lg:text-5xl xl:text-6xl text-black-gray font-Playfair-Display xxxl:text-7xl"
        >
          Our professional
          <div class="text-orange">
            get you home
          </div>
          faster & easier!
        </div>
        <div class="max-w-sm font-medium xl:max-w-lg xxl:text-xl font-Inter text-gray">
          Now, you can find more than 10,000+property choices with our
          professional agents!
        </div>
        <div class="flex items-center space-x-1 text-xs font-medium sm:text-lg smd:space-x-4 text-gray">
          <div class="">
            I want to
          </div>
          <div class="flex items-center font-bold text-black">
            <div class="mr-3">
              <svg
                width="12"
                height="9"
                viewBox="0 0 12 9"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M1 1L6 7L11 1"
                  stroke="black"
                  stroke-width="2"
                  stroke-linecap="round"
                />
              </svg>
            </div>
            Buy
          </div>
          <div class="">
            I’m looking in
          </div>
          <div class="inline font-bold text-black border-b-2 border-orange">
            Sydney
          </div>
        </div>
        <div class="flex items-center space-x-8 ">
          <div
            class="flex items-center px-12 py-3 text-white rounded-full bg-orange"
          >
            Next
          </div>
          <div class="flex items-center ">
            <div class="">
              <svg
                class=" animate-bounce"
                width="28"
                height="28"
                viewBox="0 0 28 28"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M14 2.25C19.385 2.25 23.75 6.615 23.75 12C23.75 16.12 20.855 20.61 15.14 25.518C14.8222 25.791 14.4171 25.9409 13.9981 25.9405C13.5792 25.9402 13.1743 25.7895 12.857 25.516L12.479 25.188C7.017 20.408 4.25 16.028 4.25 12C4.25 6.615 8.615 2.25 14 2.25ZM14 8.25C13.0054 8.25 12.0516 8.64509 11.3483 9.34835C10.6451 10.0516 10.25 11.0054 10.25 12C10.25 12.9946 10.6451 13.9484 11.3483 14.6517C12.0516 15.3549 13.0054 15.75 14 15.75C14.9946 15.75 15.9484 15.3549 16.6517 14.6517C17.3549 13.9484 17.75 12.9946 17.75 12C17.75 11.0054 17.3549 10.0516 16.6517 9.34835C15.9484 8.64509 14.9946 8.25 14 8.25Z"
                  fill="#FF8227"
                />
              </svg>
            </div>
            Find near me
          </div>
        </div>
      </div>

      <div class="relative mt-4 md:mt-0 md:-mr-20 md:block">
        <img
          data-aos="zoom-in"
          data-aos-offset="300"
          data-aos-easing="ease-in-sine"
          data-aos-duration="2000"
          class="absolute bottom-0 left-0 hidden md:-mb-8 md:-ml-8 lg:flex lg:-mb-20 lg:-ml-20"
          src="/bg-layer.png"
          alt=""
        >
        <img
          class="absolute bottom-0 right-0 -mb-60"
          src="/Ellipse 3.png"
          alt=""
        >

        <div class="relative">
          <div
            data-aos-offset="300"
            data-aos-easing="ease-in-sine"
            data-aos="zoom-out-down"
            data-aos-duration="2000"
            class="absolute z-30 flex items-end w-24 h-full m-4 delay-1000 md:items-center md:-ml-8 lg:w-auto lg:-ml-20 "
          >
            <div class="relative">
              <img
                class="absolute right-0 -mt-3 -mr-3"
                src="/tick.png"
                alt=""
              >
              <img
                class="absolute right-0 -mt-3 -mr-3 animate-ping"
                src="/tick.png"
                alt=""
              >
              <img class="shadow" src="/Group 299.png" alt="">
            </div>
          </div>

          <div
            data-aos="zoom-out-up"
            data-aos-easing="linear"
            data-aos-duration="2000"
            class="absolute right-0 z-30 w-40 m-4 delay-1000 md:mr-20 md:mt-10 lg:mt-20 lg:w-auto"
          >
            <div class="relative">
              <img
                class="absolute right-0 -mt-3 -mr-3 animate-ping"
                src="/tick.png"
                alt=""
              > <img
                class="absolute right-0 -mt-3 -mr-3"
                src="/tick.png"
                alt=""
              >
              <img class="w-full" src="/Group 63.png" alt="">
            </div>
          </div>

          <!-- <div class="">
          .
        </div> -->
          <img
            data-aos="zoom-in"
            data-aos-easing="linear"
            data-aos-duration="2000"
            class="z-20 w-full -ml-1"
            src="/house.png"
            alt=""
          >
        </div>

        <!-- <div class="dot" /> -->
      </div>
    </div>

    <!--  -->

    <div class="pb-20 mt-32 space-y-8 ">
      <div
        class="text-5xl font-bold text-center font-Playfair-Display text-black-gray"
      >
        Meet our professional
      </div>
      <div
        class="max-w-2xl mx-auto text-lg text-center font-Inter text-gray"
      >
        Lorem ipsum sit dolor amet consecture alien untlaasana ulalal ulili
        saiyalake Lorem ipsum sit dolor amet consecture alien.
      </div>

      <div class="grid gap-8 text-center md:grid-cols-3 text-black-gray">
        <div class="">
          <img class="w-full" src="/Mask Group (2).png" alt="">
          <div class="">
            <div class="text-xl font-medium ">
              Sarah Donin
            </div>
            <div class="">
              Managing Director
            </div>
          </div>
        </div>

        <div class="">
          <img class="w-full" src="/placeholder.png" alt="">
          <div class="w-full">
            <div class="text-xl font-medium ">
              Lindsey Botosh
            </div>
            <div class="">
              National Web Assistant
            </div>
          </div>
        </div>

        <div class="">
          <img class="w-full" src="/placeholder (1).png" alt="">
          <div class="">
            <div class="text-xl font-medium ">
              Phillip Schleifer
            </div>
            <div class="">
              National Intranet Specialist
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import aosMixin from '~/mixins/aos'

export default {
  mixins: [aosMixin],
  layout: 'deafult'
}
</script>
<style scoped>

@media (min-width: 1280px) {
  .i {
  background-image: url("/not.svg");
  background-repeat: no-repeat;
  position: center;
  display: flex;
}
}
</style>
