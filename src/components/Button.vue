<template>
    <button @click="onClick()" :style="{background: color}"  class="btn">{{text}}</button>
</template>

<script>
    export default {
        name: 'Button',
        props: {
            color: String,
            text: String,
        },
        methods: {
            onClick() {
                console.log('click');
            }
        }
    }
</script>