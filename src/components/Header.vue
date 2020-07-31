<template>
  <header 
    id="austin-anthem-header" 
    class="fixed-top"
  >
    <img 
      src="@/assets/nav/anthem-logo-navigation.png"
      class="anthem-logo"
    />

    <section class="anthem-nav-links">
      <!-- nav links -->
    </section>

    <section class="anthem-lang-login">
      <!-- language and login links -->
    </section>
  </header>
</template>

<script>
export default {
  name: 'Header'
};
</script>

<style lang="scss" scoped>
@import '../styles/palette';

#austin-anthem-header {
  background-color: $black;
  color: #fff;
  display: flex;
  padding: .5em 1em;
}

.fixed-top {
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
}

.anthem-logo {
  max-height: 50px;
}
</style>
