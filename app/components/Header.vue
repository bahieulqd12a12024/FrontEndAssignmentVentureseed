<template>
  <div
    class="flex px-6 py-4 lg:px-[120px] py-10 justify-between items-center self-stretch bg-[#42389E]"
  >
    <div class="flex items-center">
      <div class="text-white text-[18px] font-bold">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="64"
          height="60"
          viewBox="0 0 64 60"
          fill="none"
        >
          <path
            d="M14.5 4.5V48.3092M32.5 55.3V31.5312V13.8211H4.5H59"
            stroke="white"
            stroke-width="9"
            stroke-linecap="round"
          />
        </svg>
      </div>
      <div
        class="text-white text-center font-[family-name:var('Merriweather_Sans')] text-[18px] lg:text-[24px] font-bold leading-normal"
      >
        IntelliToggle
      </div>
    </div>

    <div class="hidden lg:flex items-center gap-7">
      <div
        class="text-white text-center font-[family-name:var('DM_Sans')] text-[20px] font-bold leading-normal"
      >
        Home
      </div>
      <div
        class="text-white text-center font-[family-name:var('DM_Sans')] text-[20px] font-light leading-normal"
      >
        About
      </div>
      <div
        class="text-white text-center font-[family-name:var('DM_Sans')] text-[20px] font-light leading-normal"
      >
        Pricing
      </div>
    </div>

    <div
      class="hidden lg:flex justify-center px-6 py-3 items-center gap-[10px] rounded-lg bg-[#F9A71E] shadow-[0_0_10px_10px_rgba(0,0,0,0.05)]"
    >
      <div
        class="font-[family-name:var('Inter')] text-2xl font-semibold leading-normal"
      >
        Start Sandbox
      </div>
    </div>

    <div class="w-6 h-6 flex justify-center px-6 py-3 items-center relative">
      <div
        class="w-3 h-0 left-[4px] top-[5px] absolute outline outline-[1.50px] outline-offset-[-0.75px] outline-white"
      ></div>
      <div
        class="w-4 h-0 left-[4px] top-[12px] absolute outline outline-[1.50px] outline-offset-[-0.75px] outline-white"
      ></div>
      <div
        class="w-2 h-0 left-[4px] top-[19px] absolute outline outline-[1.50px] outline-offset-[-0.75px] outline-white"
      ></div>
    </div>
  </div>
</template>
