<template>
  <div>hello {{ world }}</div>
</template>

<script lang="ts" setup>
import {
  computed,
} from "#imports";

const world = computed( () => "world" );
</script>