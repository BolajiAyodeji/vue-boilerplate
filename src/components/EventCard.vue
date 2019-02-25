<template>
  <h1 @click="handler(arg, event)">Event Card</h1>
</template>

<script>
export default {
    props: {
        propName: {
            type: Number,
            default: 2,
        },
    },
    data() {
        return {
            key: 'value',
        }
    },
}
</script>

<style></style>
