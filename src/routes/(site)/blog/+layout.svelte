<script lang="ts">
	import '../../styles.css';
	import PageTransition from '../../transition.svelte'
	import Sidebar from '../sidebar.svelte'

	export let data: {url:string}
</script>



<main class="flex">
	<Sidebar></Sidebar>
	<div class="w-full">
		<PageTransition url={data.url}>
			<slot />
		</PageTransition>
	</div>

</main>

<!--	<footer>-->
<!--		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>-->
<!--	</footer>-->
