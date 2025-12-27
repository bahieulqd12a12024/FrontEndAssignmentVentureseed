  <script setup>
    const features = [
      {
        title: "AutoFlag AI (LLM-Assisted Flag Creation)",
        desc: "Create new flags just by typing what you need. The AI names, sets rules, and configures targeting for you.",
      },
      {
        title: "SmartRamp AI (AI-Driven Rollout Optimization)",
        desc: "Rollouts that adjust themselves. AI expands, pauses, or rolls back based on real-time metrics.",
      },
      {
        title: "ExplainFlags AI (LLM Root-Cause + Insights)",
        desc: "Understand issues instantly with AI-generated, plain-language insights tied to your flags.",
      },
      {
        title: "AutoSegment AI (Behavioral Segmentation)",
        desc: "Target the right users automatically. AI builds segments from live behavior—no manual rules.",
      },
    ];
  </script>

<template>


  <section class="relative overflow-hidden py-14 sm:py-16 text-white">
    <img
      src="/homepage/AIFlaggingFeature/image.png"
      alt=""
      class="absolute inset-0 -z-10 h-full w-full object-cover"
    />
    <div class="absolute inset-0 -z-10 bg-indigo-950/70"></div>

    <div class="mx-auto max-w-6xl px-6">
      <div class="flex justify-center">
        <span
          class="rounded-full bg-amber-400 px-4 py-1 text-xs font-semibold text-indigo-950"
        >
          Coming Soon
        </span>
      </div>

      <h2 class="mt-4 text-center text-2xl font-bold sm:text-3xl">
        DartCodeAI That Actually Changes Flagging
      </h2>

      <div class="mt-10 grid gap-5 sm:gap-6 lg:grid-cols-2">
        <div
          v-for="f in features"
          :key="f.title"
          class="rounded-xl border border-white/15 bg-white/5 p-5 sm:p-6"
        >
          <h3 class="text-sm font-semibold sm:text-base">{{ f.title }}</h3>
          <p class="mt-2 text-xs leading-relaxed text-white/75 sm:text-sm">
            {{ f.desc }}
          </p>
        </div>
      </div>

      <p class="mt-10 text-center text-sm font-semibold text-amber-400">
        Enterprise Only
      </p>

      <div class="mt-6 rounded-xl border border-white/10 bg-white/5 p-4 sm:p-5">
        <div
          class="flex flex-col gap-3 sm:flex-row sm:items-center sm:justify-between"
        >
          <p class="text-sm text-white/85">
            Be The First To Try Out Our New AI Features.
          </p>

          <div
            class="flex w-full flex-col gap-3 sm:w-auto sm:flex-row sm:items-center"
          >
            <input
              type="email"
              placeholder="Enter email address"
              class="h-11 w-full rounded-md border border-white/15 bg-white/10 px-4 text-sm text-white placeholder:text-white/50 sm:w-64"
            />
            <button
              class="inline-flex h-11 w-full items-center justify-center rounded-md bg-amber-400 px-5 text-sm font-semibold text-indigo-950 sm:w-auto"
              type="button"
            >
              Join AI Early Access
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
