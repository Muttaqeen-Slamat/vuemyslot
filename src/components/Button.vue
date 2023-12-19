<template>
    <div>
        <button>
            <slot name="text"></slot>
            <slot></slot>
        </button>
    </div>
</template>

<script>
    export default {
        name: 'ButtonComp'
    }
</script>

<style scoped>

</style>