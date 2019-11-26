<template>
  <main>
    <px-header />
    <px-assets-table />
  </main>
</template>

<script>
import PxHeader from "@/components/PxHeader";
import PxAssetsTable from "@/components/PxAssetsTable";

export default {
  name: "app",
  components: { PxHeader, PxAssetsTable }
};
</script>

<style></style>
