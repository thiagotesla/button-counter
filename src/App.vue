<script>
import ButtonCounter from './components/ButtonCounter.vue'
  
export default {
  components: {
    ButtonCounter
  }
}
</script>

<template>
	<h1 class="center">Here are many child components!</h1>
		<div class="center">
		<ButtonCounter />
		<ButtonCounter />
		<ButtonCounter />
	</div>
</template>

<style>
	.center{
		text-align: center;
	}

</style>