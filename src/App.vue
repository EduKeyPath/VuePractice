
<template>
  <div>
    <HeaderBar />
    <router-view/>
    <FooterBar />
  </div>
</template>

<script>
import HeaderBar from './components/Header';
import FooterBar from './components/Footer';

export default {
  name: 'App',
  components : {HeaderBar, FooterBar}
}
</script>

<style>

</style>
