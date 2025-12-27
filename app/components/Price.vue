<template>
  <section class="hidden lg:block bg-slate-100 py-12 sm:py-16">
    <div class="mx-auto max-w-6xl px-6">
      <h2 class="text-center text-xl font-bold text-indigo-950 sm:text-2xl">
        Plans Built For Every Stage Of Growth
      </h2>

      <div class="mt-8 flex flex-col items-center">
        <div class="w-full max-w-xs rounded-xl bg-gradient-to-b from-indigo-700 to-slate-950 px-6 py-5 text-center text-white shadow-lg">
          <p class="text-sm font-semibold text-white/90">Price starts at</p>
          <div class="mt-2 flex items-end justify-center gap-2">
            <span class="text-3xl font-bold">$10</span>
            <span class="pb-1 text-sm text-white/80">/month</span>
          </div>
        </div>

        <button class="mt-4 inline-flex w-fit items-center justify-center rounded-md bg-amber-400 px-5 py-2 text-sm font-semibold text-indigo-950 shadow-sm">
          View Subscription Details
        </button>
      </div>

      <div class="mt-10 rounded-xl border border-slate-200 bg-white px-5 py-6 shadow-sm sm:px-8">
        <div class="flex flex-col gap-5 sm:flex-row sm:items-center sm:justify-between">
          <div>
            <h3 class="text-base font-semibold text-slate-900 sm:text-lg">
              Start Your 7-Day Free Sandbox Plan
            </h3>
            <p class="mt-1 text-sm text-slate-600">
              Join over 1,000+ startups already growing with Untitled.
            </p>
          </div>

          <div class="flex flex-col gap-3 sm:flex-row sm:items-center">
            <button class="h-11 w-full rounded-md bg-amber-400 px-6 text-sm font-semibold text-indigo-950 sm:w-auto">
              Get Started
            </button>
            <button class="h-11 w-full rounded-md border border-amber-400 px-6 text-sm font-semibold text-amber-600 sm:w-auto">
              Learn More
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="block lg:hidden px-4 py-10">
    <h2 class="mb-6 text-center text-xl font-semibold text-indigo-950">
      Control & Power-focused
    </h2>

    <div class="mx-auto max-w-sm rounded-2xl bg-gradient-to-b from-indigo-800 to-slate-900 p-6 text-white shadow-xl">
      <div class="mb-4 flex items-center justify-between">
        <span class="rounded-full bg-amber-400 px-3 py-1 text-sm font-semibold text-neutral-900">
          Popular
        </span>
        <span class="-rotate-12 rounded-full bg-white/90 px-3 py-1 text-xs font-semibold text-indigo-800">
          Billed annually
        </span>
      </div>

      <h3 class="mb-4 text-lg font-semibold">Enhance Plan</h3>

      <div class="mb-6 flex items-end gap-2">
        <span class="text-4xl font-bold">$149</span>
        <span class="mb-1 text-sm opacity-80">/month</span>
      </div>

      <ul class="mb-6 space-y-3 text-sm leading-relaxed">
        <li>✓ Multi-environment support (Dev / Staging / Prod)</li>
        <li>✓ Unlimited feature flags and projects</li>
        <li>✓ Advanced targeting rules with custom attributes</li>
        <li>✓ Environment-specific flags</li>
        <li>✓ Real-time streaming updates (WebSocket / gRPC)</li>
        <li>✓ Analytics hooks (flag usage tracking)</li>
        <li>✓ Built-in A/B testing / experimentation dashboard</li>
        <li>✓ Audit logs (90-day retention + export)</li>
        <li>✓ API access with multiple keys & custom roles</li>
      </ul>

      <button class="w-full rounded-lg border border-white/80 py-3 text-sm font-semibold">
        Subscribe
      </button>
    </div>
  </section>

</template>
