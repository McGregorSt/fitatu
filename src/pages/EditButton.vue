<template>
    <div>
        <button @click="handleClick"> Edit </button>
    </div>
</template>

<script>
export default {
    methods: {
        handleClick(e) {
            console.log(this._uid);

            
        }
    }
}
</script>

<style>

</style>
