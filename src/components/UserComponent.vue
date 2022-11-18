<script>
export default {
  name: "HomeView",
  props: ["displayName", "img", "followers"],
};
</script>

<template>
  <div>
    {{ displayName }}
  </div>
  <div>
    {{ img }}
  </div>
  <div>
    {{ followers }}
  </div>
</template>
