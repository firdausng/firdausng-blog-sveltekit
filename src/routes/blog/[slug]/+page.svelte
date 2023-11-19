<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;
</script>

<article class="container mx-auto">
	<header class="p-2">
		<h1 class="text-3xl underline underline-offset-8">{data.post.title}</h1>
	</header>
	<!-- render the post -->
	<div class="prose dark:prose-invert w-full p-4">
		<svelte:component this={data.component} />
	</div>
</article>