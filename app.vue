<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup>
import { onMounted } from "vue";
import { useFlowbite } from "~/composables/useFlowbite";
onMounted(() => {
  useFlowbite(() => {
    initFlowbite();
  });
});
useHead({
  bodyAttrs: {
    class: "bg-slate-800 text-white",
  },
});
</script>
