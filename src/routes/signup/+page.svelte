<script lang="ts">
	import Header from '$lib/Header.svelte';
	import SignupForm from './SignupForm.svelte';
	import WelcomeNavigator from '$lib/WelcomeNavigator.svelte';
</script>

<Header>
	<WelcomeNavigator />
</Header>

<div class="columns">
	<div class="column">
		<div class="box">
			<h1 class="title">Sign Up!</h1>
			<SignupForm />
		</div>
	</div>
	<div class="column has-text-centered">
		<img alt="signup" src="/sign up.jpeg" width="400" />
	</div>
</div>