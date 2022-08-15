<script setup>
import { ref } from "vue";

defineProps({
	msg: String,
});

const count = ref(0);
</script>

<template lang="pug">
.block hello
</template>

<style lang="scss" scoped>
@import "../assets/main.scss";
</style>
