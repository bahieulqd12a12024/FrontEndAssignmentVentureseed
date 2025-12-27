<script setup>
const resources = [
  "Why IntelliToggle Is Different",
  "Customer Support",
  "Terms & Conditions",
  "Privacy Policy",
]
const company = ["Pricing", "Documentation", "About Us"]
</script>

<template>
  <footer class="bg-slate-100 py-10 sm:py-12">
    <div class="mx-auto px-6">
      <div class="grid gap-10 lg:grid-cols-4 lg:items-start">
        <div class="space-y-4">
          <div class="flex items-center gap-3">
            <div class="h-10 w-10 rounded-md bg-contain bg-no-repeat"
                 style="background-image:url('/homepage/footer/IntelliToggle.png')"
            ></div>
            <span class="text-base font-semibold text-indigo-800">IntelliToggle</span>
          </div>

          <p class="max-w-xs text-sm text-neutral-600">
            IntelliToggle is built by AORTEM, a company focused on powering scalable,
            multi-platform developer tools.
          </p>

          <button
            class="inline-flex h-9 w-9 items-center justify-center rounded-full bg-contain bg-no-repeat"
            type="button"
            style="background-image:url('/homepage/footer/Github.png')"
          ></button>
        </div>

        <div class="grid gap-10 sm:grid-cols-2 lg:col-span-2">
          <div>
            <p class="text-xs font-semibold text-zinc-600">Resources</p>
            <ul class="mt-4 space-y-3">
              <li v-for="t in resources" :key="t">
                <a href="#" class="text-sm font-semibold text-neutral-700">
                  {{ t }}
                </a>
              </li>
            </ul>
          </div>

          <div>
            <p class="text-xs font-semibold text-zinc-600">Company</p>
            <ul class="mt-4 space-y-3">
              <li v-for="t in company" :key="t">
                <a href="#" class="text-sm font-semibold text-neutral-700">
                  {{ t }}
                </a>
              </li>
            </ul>
          </div>
        </div>

        <div class="space-y-4">
          <p class="text-xs font-semibold text-gray-800">Subscribe to Newsletter</p>

          <div class="flex w-full max-w-sm overflow-hidden rounded-md border border-slate-200 bg-white">
            <input
              type="email"
              placeholder="Enter email address"
              class="h-10 w-full px-4 text-sm text-zinc-500 outline-none"
            />
            <button class="h-10 shrink-0 bg-amber-500 px-5 text-sm font-semibold text-indigo-800">
              Subscribe
            </button>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
