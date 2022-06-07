<script setup>
const tag = '6449073';
const action =
  'https://snapshot.us17.list-manage.com/subscribe/post?u=1c820b717ffe37c1703e33f4b&amp;id=f11d6e5df6';
</script>
<template>
  <form
    :action="action"
    method="post"
    target="_blank"
    autocomplete="off"
    class="relative max-w-[320px]"
  >
    <input type="hidden" name="tags" :value="tag" />
    <input
      type="email"
      name="EMAIL"
      class="border rounded-full py-2 px-3 text-md w-full"
      placeholder="Your email"
      required
    />
    <button
      class="absolute right-0 p-2 bg-skin-text rounded-r-full px-[14px] h-[46px] top-[1px]"
      type="submit"
      name="subscribe"
    >
      <IH-paper-airplane class="text-white w-[28px] h-[28px] rotate-90" />
    </button>
  </form>
</template>
