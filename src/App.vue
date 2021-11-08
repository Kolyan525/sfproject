<template>
  <div>
    <InventoryOrganizer/>
    <WorkWithUs/>
  </div>
</template>

<script>
import InventoryOrganizer from "./components/InventoryOrganizer";
import WorkWithUs from "./components/WorkWithUs";

export default {
  components: {
    InventoryOrganizer,
    WorkWithUs
  },
  name: "App"
};
</script>
