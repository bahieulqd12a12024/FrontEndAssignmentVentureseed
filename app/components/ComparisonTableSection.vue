<script setup>
const rows = [
  { feature: "Dart-native SDK & server", intelli: true, other: false },
  { feature: "End-to-end type safety", intelli: true, other: false },
  { feature: "AI-assisted roll-outs & cleanup", intelli: true, other: false },
  { feature: "A/B testing built-in", intelli: true, other: false },
  { feature: "Dart-Powered SDKs", intelli: true, other: false },
]

const mark = (v) => (v ? "✓" : "✗")
</script>


<template>
  <section class="py-12">
    <div class="mx-auto max-w-5xl px-6">
      
      <p class="text-center text-4xl font-bold text-indigo-800">
        Dart-Powered Feature Flag
      </p>

      <h2 class="mt-3 text-center text-xl font-bold text-slate-900 sm:text-2xl">
        Not Another Generic Feature Flag Tool
      </h2>

      <p class="mx-auto mt-3 max-w-2xl text-center text-sm text-slate-600">
        Most tools are built for every language, which means extra layers and slower toggles.
        IntelliToggle is built in Dart, for Dart — so it's faster, safer, and built for your stack.
      </p>

      
      <div class="mt-8 overflow-x-auto">
        <table class="w-full min-w-[640px] border-collapse overflow-hidden rounded-lg">
          <thead>
            <tr class="bg-indigo-950 text-white">
              <th class="px-4 py-3 text-left text-sm font-semibold">Features</th>
              <th class="px-4 py-3 text-center text-sm font-semibold">IntelliToggle</th>
              <th class="px-4 py-3 text-center text-sm font-semibold">Other Feature Flag</th>
            </tr>
          </thead>

          <tbody class="bg-slate-50">
            <tr
              v-for="(r, i) in rows"
              :key="r.feature"
              class="border-t border-slate-200"
              :class="i === rows.length - 1 ? 'rounded-b-lg' : ''"
            >
              <td class="px-4 py-3 text-sm text-slate-700">
                {{ r.feature }}
              </td>
              <td class="px-4 py-3 text-center text-sm font-semibold text-slate-900">
                {{ mark(r.intelli) }}
              </td>
              <td class="px-4 py-3 text-center text-sm font-semibold text-slate-900">
                {{ mark(r.other) }}
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </section>
</template>

