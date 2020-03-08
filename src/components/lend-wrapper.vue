<template>
    <div class="lend-wrapper">
        <lend-nav/>
        <lend-initial-screen/>

    </div>
    
</template>

<script>
import lendNav from './lend-nav'
import lendInitialScreen from './lend-initial-screen'

export default {
    name: 'lend-wrapper',
    components: {
        lendNav,
        lendInitialScreen,
    }
    
}
</script>

<style>
.lend-wrapper {
    display: grid;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    
}
.conteiner {
    display: grid;
    width: 1fr;
    max-width: 1200px;
    min-width: 320;
    padding: 15px;
    justify-self: stretch;
}

</style>