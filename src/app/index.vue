<template>
    <router-view />
</template>

<script>
export default {
    name: 'app'
}
</script>

<style lang="scss">
    @import "~@coreui/icons/css/coreui-icons.min.css";
    /* Import Font Awesome Icons Set */
    $fa-font-path: '~font-awesome/fonts/';
    @import '~font-awesome/scss/font-awesome.scss';
    /* Import Simple Line Icons Set */
    $simple-line-font-path: '~simple-line-icons/fonts/';
    @import '~simple-line-icons/scss/simple-line-icons.scss';
    /* Import Flag Icons Set */
    @import '~flag-icon-css/css/flag-icon.min.css';
    @import "~bootstrap-vue/dist/bootstrap-vue.css";
    @import '../assets/scss/style';
</style>