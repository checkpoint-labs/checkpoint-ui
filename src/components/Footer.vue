<script setup>
import { twitter, discord, telegram, github } from '@/constants.json';
</script>

<template>
  <div class="border-t">
    <Container class="py-4 text-[19px] text-center sm:flex">
      <div class="sm:text-left flex-auto mb-3 sm:mb-0">
        Made with
        <IH-heart class="text-red w-[28px] h-[28px] inline-block" />
        by Snapshot
      </div>
      <div class="space-x-3">
        <a :href="twitter" target="_blank">
          <img
            src="~@/assets/twitter.svg?cb=1"
            class="w-[30px] h-[30px] inline-block"
          />
        </a>
        <a :href="discord" target="_blank">
          <img
            src="~@/assets/discord.svg?cb=1"
            class="w-[30px] h-[30px] inline-block"
          />
        </a>
        <a :href="telegram" target="_blank">
          <img
            src="~@/assets/telegram.svg?cb=1"
            class="w-[30px] h-[30px] inline-block"
          />
        </a>
        <a :href="github" target="_blank">
          <img
            src="~@/assets/github.svg?cb=1"
            class="w-[30px] h-[30px] inline-block"
          />
        </a>
      </div>
    </Container>
  </div>
</template>
