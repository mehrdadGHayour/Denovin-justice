<template>
  <header class="z-20">
    <div
      class="container mx-auto flex justify-between items-center px-10 lg:px-32 py-5">
      <img class="z-10" src="/images/Logo.png" alt="logo" />
      <div class="flex items-center gap-5 z-[3]">
        <nav
          class="navbar w-[690px] h-[83px] bg-white/30 backdrop-blur rounded-full flex items-center justify-center max-lg:hidden">
          <ul
            class="flex justify-center item-center flex-col p-4 md:p-0 mt-4 border rounded-lg md:flex-row md:space-x-8 md:mt-0 md:border-0 text-black/50">
            <li class="">
              <a
                href="#"
                class="py-2 pl-3 pr-4 rounded text-black flex justify-center relative after:absolute after:-bottom-1 after:bg-black after:h-1 after:rounded after:w-5"
                aria-current="page"
                >درباره من</a
              >
            </li>
            <li class="">
              <a
                href="#"
                class="block py-2 pl-3 pr-4 rounded"
                aria-current="page"
                >ویدیو معرفی</a
              >
            </li>
            <li class="">
              <a
                href="#"
                class="block py-2 pl-3 pr-4 rounded"
                aria-current="page"
                >گالری تصاویر</a
              >
            </li>
            <li class="">
              <a
                href="#"
                class="block py-2 pl-3 pr-4 rounded"
                aria-current="page"
                >کلاس ها</a
              >
            </li>
            <li class="">
              <a
                href="#"
                class="block py-2 pl-3 pr-4 rounded"
                aria-current="page"
                >کتاب و مقاله</a
              >
            </li>
          </ul>
        </nav>
        <div class="flex gap-3 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none">
            <g clip-path="url(#clip0_3944_4545)">
              <mask
                id="mask0_3944_4545"
                style="mask-type: luminance"
                maskUnits="userSpaceOnUse"
                x="0"
                y="0"
                width="24"
                height="24">
                <path
                  d="M12 24C18.6274 24 24 18.6274 24 12C24 5.37258 18.6274 0 12 0C5.37258 0 0 5.37258 0 12C0 18.6274 5.37258 24 12 24Z"
                  fill="white" />
              </mask>
              <g mask="url(#mask0_3944_4545)">
                <path
                  d="M0 0L0.375 1.03125L0 2.10938V3.1875L1.5 5.71875L0 8.25V9.75L1.5 12L0 14.25V15.75L1.5 18.2812L0 20.8125V24L1.03125 23.625L2.10938 24H3.1875L5.71875 22.5L8.25 24H9.75L12 22.5L14.25 24H15.75L18.2812 22.5L20.8125 24H24L23.625 22.9688L24 21.8906V20.8125L22.5 18.2812L24 15.75V14.25L22.5 12L24 9.75V8.25L22.5 5.71875L24 3.1875V0L22.9688 0.375L21.8906 0H20.8125L18.2812 1.5L15.75 0H14.25L12 1.5L9.75 0H8.25L5.71875 1.5L3.1875 0H0Z"
                  fill="#EEEEEE" />
                <path
                  d="M15.75 0V5.0625L20.8125 0H15.75ZM24 3.1875L18.9375 8.25H24V3.1875ZM0 8.25H5.0625L0 3.1875V8.25ZM3.1875 0L8.25 5.0625V0H3.1875ZM8.25 24V18.9375L3.1875 24H8.25ZM0 20.8125L5.0625 15.75H0V20.8125ZM24 15.75H18.9375L24 20.8125V15.75ZM20.8125 24L15.75 18.9375V24H20.8125Z"
                  fill="#0052B4" />
                <path
                  d="M0 0V2.10938L6.14062 8.25H8.25L0 0ZM9.75 0V9.75H0V14.25H9.75V24H14.25V14.25H24V9.75H14.25V0H9.75ZM21.8906 0L15.75 6.14062V8.25L24 0H21.8906ZM8.25 15.75L0 24H2.10938L8.25 17.8594V15.75ZM15.75 15.75L24 24V21.8906L17.8594 15.75H15.75Z"
                  fill="#D80027" />
              </g>
            </g>
            <defs>
              <clipPath id="clip0_3944_4545">
                <rect width="24" height="24" fill="white" />
              </clipPath>
            </defs>
          </svg>
          <h2 class="max-lg:hidden">ENG</h2>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="10"
            height="6"
            viewBox="0 0 10 6"
            fill="none"
            class="max-lg:hidden">
            <path
              opacity="0.3"
              d="M1 0.735352L4.81717 4.55253C4.91815 4.6535 5.08185 4.6535 5.18283 4.55253L9 0.735352"
              stroke="black"
              stroke-width="0.833333"
              stroke-linecap="round" />
          </svg>
          <div class="max-lg:hidden">
            <button
              class="rounded-lg bg-gold p-2 flex items-center text-white gap-2"
              dir="ltr">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="21"
                height="21"
                viewBox="0 0 21 21"
                fill="none">
                <path
                  opacity="0.4"
                  d="M12.6475 2.3374C15.6931 2.67562 18.0993 5.07854 18.4409 8.12415"
                  stroke="white"
                  stroke-width="1.36207"
                  stroke-linecap="round"
                  stroke-linejoin="round" />
                <path
                  opacity="0.4"
                  d="M12.6475 5.25293C14.1049 5.53601 15.2438 6.67575 15.5277 8.13314"
                  stroke="white"
                  stroke-width="1.36207"
                  stroke-linecap="round"
                  stroke-linejoin="round" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M9.91424 10.5438C13.1968 13.8256 13.9415 10.029 16.0316 12.1176C18.0465 14.1321 19.2055 14.5357 16.6517 17.088C16.3319 17.3449 14.3002 20.4368 7.1599 13.2984C0.0187326 6.15903 3.10876 4.12514 3.36582 3.80544C5.92495 1.24609 6.32246 2.41096 8.33743 4.42541C10.4266 6.51493 6.63164 7.26208 9.91424 10.5438Z"
                  stroke="white"
                  stroke-width="1.36207"
                  stroke-linecap="round"
                  stroke-linejoin="round" />
              </svg>
              021_91016668
            </button>
          </div>
        </div>
        <button class="border rounded-lg p-1 bg-slate-200/10 lg:hidden">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none">
            <path
              d="M2 5.995C2 5.445 2.446 5 2.995 5L11.005 5C11.2689 5 11.522 5.10483 11.7086 5.29143C11.8952 5.47803 12 5.73111 12 5.995C12 6.25889 11.8952 6.51197 11.7086 6.69857C11.522 6.88517 11.2689 6.99 11.005 6.99L2.995 6.99C2.445 6.99 2 6.545 2 5.995ZM2 12C2 11.45 2.446 11.005 2.995 11.005L21.005 11.005C21.2689 11.005 21.522 11.1098 21.7086 11.2964C21.8952 11.483 22 11.7361 22 12C22 12.2639 21.8952 12.517 21.7086 12.7036C21.522 12.8902 21.2689 12.995 21.005 12.995L2.995 12.995C2.445 12.995 2 12.549 2 12ZM2.995 17.01C2.73111 17.01 2.47803 17.1148 2.29143 17.3014C2.10483 17.488 2 17.7411 2 18.005C2 18.2689 2.10483 18.522 2.29143 18.7086C2.47803 18.8952 2.73111 19 2.995 19L15.005 19C15.1357 19 15.2651 18.9743 15.3858 18.9243C15.5065 18.8743 15.6162 18.801 15.7086 18.7086C15.801 18.6162 15.8743 18.5065 15.9243 18.3858C15.9743 18.2651 16 18.1357 16 18.005C16 17.8743 15.9743 17.7449 15.9243 17.6242C15.8743 17.5035 15.801 17.3938 15.7086 17.3014C15.6162 17.209 15.5065 17.1357 15.3858 17.0857C15.2651 17.0357 15.1357 17.01 15.005 17.01L2.995 17.01Z"
              fill="#1E2D48" />
          </svg>
        </button>
      </div>
    </div>
  </header>

  <section></section>
</template>

<script setup></script>

<style scoped></style>
