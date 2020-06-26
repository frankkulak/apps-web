<template>
    <div id="home-page">
        <p>Hello there! This website is currently under construction. It will be used to showcase apps I make.</p>
        <p>In the meantime, please check out my <a href="https://frankkulak.com">main website</a> and the <a
                href="https://mods.frankkulak.com">website for my mods</a>.</p>
    </div>
</template>

<script>
    export default {
        name: 'HomePage'
    }
</script>

<style lang="scss">
    #home-page {
        padding-left: 20px;
        padding-right: 20px;
        width: 100vw;
        height: 100vh;
        display: table-cell;
        vertical-align: middle;
        text-align: center;

        a, a:hover, a:focus {
            color: var(--text-color);
        }
    }
</style>