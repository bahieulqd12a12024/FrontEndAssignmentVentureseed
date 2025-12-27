<template>
  <section class="py-10">
    <div class="mx-auto px-6">
      <p
        class="text-center text-2xl font-semibold text-slate-800 font-['Inter']"
      >
        Trusted by various engineering teams
      </p>

      <div
        class="mt-6 flex flex-wrap items-center justify-center gap-x-10 gap-y-6"
      >
        <img
          v-for="brand in brands"
          :key="brand.src"
          :src="brand.src"
          :alt="brand.alt"
          class="h-10 w-auto"
        />
      </div>
    </div>
  </section>
</template>

<script setup>
const brands = [
  { src: "/homepage/hero/brand/Google.png", alt: "Google Cloud" },
  { src: "/homepage/hero/brand/Amazon.png", alt: "Amazon Web Services" },
  { src: "/homepage/hero/brand/Microsoft.png", alt: "Microsoft Azure" },
  { src: "/homepage/hero/brand/DigitalOcean.png", alt: "Digital Ocean" },
  { src: "/homepage/hero/brand/IBM.png", alt: "IBM" },
];
</script>
