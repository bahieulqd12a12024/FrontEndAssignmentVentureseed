<template>
  <section class="py-12 sm:py-16">
    <div class="mx-auto px-6">
      <h2 class="text-center text-4xl font-bold text-indigo-800 sm:text-2xl">
        Control &amp; Power-focused
      </h2>

      <div class="mt-10 grid gap-8 sm:grid-cols-2 lg:grid-cols-3">
        <article
          v-for="item in items"
          :key="item.title"
          class="flex flex-col"
        >
          
          <div class="overflow-hidden rounded-xl border border-slate-200 bg-slate-50">
            <img
              :src="item.img"
              :alt="item.title"
              class="h-auto w-full object-cover"
            />
          </div>

          
          <h3 class="mt-4 text-lg font-semibold text-slate-800 sm:text-base">
            {{ item.title }}
          </h3>
          <p class="mt-1 text-xs leading-relaxed text-slate-600 sm:text-sm">
            {{ item.desc }}
          </p>

          
          <button
            class="mt-4 w-fit rounded-lg px-6 py-3 text-lg text-amber-500 outline outline-1 outline-amber-500"
            type="button"
          >
            View Documentation
          </button>
        </article>
      </div>
    </div>
  </section>
</template>



<script setup>
const items = [
  {
    img: "/homepage/controlPowerSection/Connect.png",
    title: "Connect",
    desc: "Install SDK in your Dart project in 2 mins.",
  },
  {
    img: "/homepage/controlPowerSection/Create Flags.png",
    title: "Create Flags",
    desc: "Define features in IntelliToggle dashboard.",
  },
  {
    img: "/homepage/controlPowerSection/Ship & Control.png",
    title: "Ship & Control",
    desc: "Flip switches anytime, see instant results.",
  },
]
</script>