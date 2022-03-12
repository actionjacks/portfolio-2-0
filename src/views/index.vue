<template>
  <div class="main_wiew">
    <ThemeSwitcher />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import ThemeSwitcher from "@/components/ThemeSwitcher.vue";

export default defineComponent({
  components: { ThemeSwitcher },
  setup() {
    return {};
  },
});
</script>
<style lang="scss" src="@/styles/main.scss" />
