<template>
    <div>
        <button @click="IncrementCount">Click {{count}} times</button>
    </div>
</template>

<script>
import CounterMixin from '../mixins/Counter'

    export default {
        name: 'ClickCounter',
        mixins: [CounterMixin]
    }
</script>

<style scoped>

</style>