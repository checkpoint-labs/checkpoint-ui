<template>
  <div class="border-b">
    <Container>
      <div class="py-4">
        <router-link
          :to="{ name: 'home' }"
          class="mono text-[21px] text-skin-link tracking-tighter"
        >
          <IH-flag class="text-primary w-[28px] h-[28px] inline-block" />
          checkpoint
        </router-link>
      </div>
    </Container>
  </div>
</template>
