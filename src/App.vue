<template>
  <div class="main _container">
    <div class="main__vh">
			<main-header/>
			<main-slide/>
		</div>

  <main-page/>
	
</div>
</template>

<script>
import MainSlide from './components/MainSlide.vue'
import MainHeader from './components/MainHeader.vue'
import MainPage from './components/MainPage.vue'

export default {
  name: 'App',
  components: {
    MainSlide,
    MainHeader,
    MainPage
  }
}
</script>

<style lang="scss" scoped>
.main {
  padding: 0px 15px;

  &__vh {
    min-height: 100vh;
  }
}
</style>
