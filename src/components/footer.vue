<template>
    <footer>
        Made with <a href="https://cli.vuejs.org/">Vue CLI</a> by Leo Voon | Deploy with <a href="https://www.netlify.com/">Netlify</a>
    </footer>
</template>



<style lang="scss" scoped>
    footer {
        position: absolute;
        bottom: 0;
        margin-top: 4em;
        padding: 1rem;
        background-color: gainsboro;

        a {
            text-decoration: none;
            color: mediumaquamarine;

        &:hover {
            color: gray;
        }
        }
    }
</style>