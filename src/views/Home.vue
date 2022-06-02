<script setup>
const start = 'https://docs.checkpoint.fyi/guides/quickstart';
const docs = 'https://docs.checkpoint.fyi';
const support = 'https://discord.gg/snapshot';
</script>
<template>
  <div class="py-2 flex">
    <div class="flex-auto">
      <div class="border-b">
        <div class="max-w-[720px] mx-auto px-5 overflow-hidden">
          <div class="py-4">
            <div class="mono text-[20px] text-skin-link tracking-tight">
              <IH-flag class="text-primary w-[28px] h-[28px] inline-block" />
              checkpoint
            </div>
          </div>
        </div>
      </div>
      <div class="max-w-[720px] mx-auto px-5 overflow-hidden">
        <div class="mt-8 space-y-6">
          <div class="max-w-screen-sm">
            <h1 class="mb-7 mono">
              Input events,<br />
              Output API
            </h1>
            <div class="flex mb-5 max-w-screen-xs">
              <div class="py-[10px]">
                <img
                  src="https://starkware.co/wp-content/uploads/2021/05/StarkNet-Icon.png"
                  width="52"
                  height="52"
                />
              </div>
              <div class="squares flex-auto mt-[10px]" />
              <div class="w-[72px] -mx-4 relative">
                <div
                  class="animate-pulse-fast bg-primary w-[72px] h-[72px] rounded-full absolute"
                />
                <div
                  class="bg-primary w-[52px] h-[52px] rounded-full absolute m-[10px]"
                >
                  <IH-flag
                    class="text-white left-[14px] top-[14px] w-[26px] h-[26px] absolute"
                  />
                </div>
              </div>
              <div class="circles flex-auto mt-[10px]" />
              <div class="py-[10px]">
                <IH-terminal class="w-[52px] h-[52px] text-skin-link" />
              </div>
            </div>
            <div class="mb-6 text-lg">
              Checkpoint is a library for indexing data from StarkNet events and
              making it accessible through GraphQL.
            </div>
          </div>
          <div class="overflow-hidden mb-4">
            <div class="mb-3 flex grid lg:grid-cols-3 grid-cols-2 gap-3">
              <a
                :href="start"
                target="_blank"
                class="px-4 py-3 rounded-lg block bg-black"
              >
                <IH-lightning-bolt
                  class="text-white w-[28px] h-[28px] inline-block"
                />
                <h3 class="text-white inline-block float-right">Get started</h3>
              </a>
              <a
                :href="docs"
                target="_blank"
                class="px-4 py-3 rounded-lg block bg-black"
              >
                <IH-book-open
                  class="text-white w-[28px] h-[28px] inline-block"
                />
                <h3 class="text-white inline-block float-right">Docs</h3>
              </a>
              <a
                :href="support"
                target="_blank"
                class="px-4 py-3 rounded-lg block bg-black"
              >
                <IH-support class="text-white w-[28px] h-[28px] inline-block" />
                <h3 class="text-white inline-block float-right">Support</h3>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
