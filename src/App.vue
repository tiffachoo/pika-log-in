<template>
	<pikachu />
	<div class="form-container">
		<div class="input">
			<label 
				class="input-label"
				for="user"
			>
				User name
			</label>
			<input 
				id="user" 
				class="input-control"
				type="text"
			>
		</div>
		<div class="input">
			<label 
				class="input-label"
				for="password"
			>
				Password
			</label>
			<input 
				id="password" 
				class="input-control"
				type="password"
			>
		</div>
		<button 
			aria-label="Log in"
			class="button-circle"
		>
			<svg width="7px" height="20px" viewBox="0 0 7 20">
				<polyline class="stroke button-circle-chevron" points="1.5,18.5 5.5,10 1.5,1.5 "/>
			</svg>
		</button>
	</div>
</template>

<script>
import Pikachu from '@/components/Pikachu.vue'

export default {
	name: 'App',
	components: {
		Pikachu
	}
}
</script>

<style lang="scss">
@import 'styles/styles';
</style>
