<template>
    <div>
        <button>
            <slot name="Btn"></slot>
        </button>
    </div>
    <div>
        <button class="Yellow">
            <slot name="Click"></slot>
        </button>

    </div>
</template>

<script>
export default {
    name: 'ButtonComp'
}
</script>

<style scoped>
button {
    background: red;
    border: none;
    color: aliceblue;
    border-radius: 8%;
}
.Yellow{
    background: yellow;
    border: none;
    color: black;
    border-radius: 8%;
}
</style>