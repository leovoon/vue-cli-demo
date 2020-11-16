<template>
    <footer>
        Made with <a href="https://cli.vuejs.org/">Vue CLI</a> by Leo Voon <br>Deploy with <a href="https://www.netlify.com/">Netlify</a>
    </footer>
</template>



<style lang="scss" scoped>
    footer {
        width: 100%;
        line-height: 1.5;
        margin-top: 2rem;
        padding: 1rem;
        background-color: gainsboro;
        text-align: center;
        a {
            text-decoration: none;
            color: mediumaquamarine;

        &:hover {
            color: gray;
        }
        }
    }
</style>