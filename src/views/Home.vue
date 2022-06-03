<script setup>
import { start, docs, telegram } from '@/constants.json';
</script>

<template>
  <Nav />
  <Container class="space-y-8 my-8">
    <div class="max-w-screen-sm">
      <h1 class="mb-7 mono">
        From events,<br />
        To API
      </h1>
      <div class="flex mb-5 max-w-screen-xs">
        <div class="py-[10px]">
          <img
            src="https://starkware.co/wp-content/uploads/2021/05/StarkNet-Icon.png"
            width="64"
            height="64"
          />
        </div>
        <div class="squares flex-auto mt-3" />
        <div class="w-[72px] -mx-4 relative">
          <div
            class="animate-pulse-fast opacity-90 bg-primary w-[84px] h-[84px] rounded-full absolute"
          />
          <div
            class="bg-primary w-[64px] h-[64px] rounded-full absolute m-[10px]"
          >
            <IH-flag
              class="text-white left-[18px] top-[18px] w-[28px] h-[28px] absolute"
            />
          </div>
        </div>
        <div class="circles flex-auto mt-3" />
        <div class="py-[10px]">
          <IH-terminal class="w-[64px] h-[64px] text-skin-link" />
        </div>
      </div>
      <p class="text-lg">
        Checkpoint is a library for indexing data from StarkNet events and
        making it accessible through GraphQL.
      </p>
    </div>
    <div class="overflow-hidden">
      <div class="flex grid lg:grid-cols-3 md:grid-cols-2 grid-cols-1 gap-3">
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
          <IH-book-open class="text-white w-[28px] h-[28px] inline-block" />
          <h3 class="text-white inline-block float-right">Docs</h3>
        </a>
        <a
          :href="telegram"
          target="_blank"
          class="px-4 py-3 rounded-lg block bg-black"
        >
          <IH-support class="text-white w-[28px] h-[28px] inline-block" />
          <h3 class="text-white inline-block float-right">Support</h3>
        </a>
      </div>
    </div>
    <div class="overflow-hidden">
      <div class="grid grid-cols-3">
        <div class="col-span-2">
          <h2 class="mb-2">Open source</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
            <a>Learn more</a>
          </p>
        </div>
        <div class="text-center py-4">
          <IH-globe class="text-primary w-[90px] h-[90px] inline-block" />
        </div>
      </div>
    </div>
    <div class="overflow-hidden">
      <div class="grid grid-cols-3">
        <div class="text-center py-4">
          <IH-code class="text-primary w-[90px] h-[90px] inline-block" />
        </div>
        <div class="col-span-2">
          <h2 class="mb-2">Contribute</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
            <a>Learn more</a>
          </p>
        </div>
      </div>
    </div>
  </Container>
  <Container slim class="mb-8">
    <div class="bg-skin-border rounded-0 md:rounded-md grid grid-cols-3">
      <div class="col-span-2 px-5 py-4">
        <h2 class="mb-2">Join the newsletter</h2>
        <input
          type="email"
          class="border rounded-full py-2 px-3 text-md w-full max-w-[320px]"
          placeholder="Your email"
        />
      </div>
      <div class="text-center py-5">
        <IH-mail class="text-primary w-[90px] h-[90px] inline-block" />
      </div>
    </div>
  </Container>
  <Footer />
</template>
