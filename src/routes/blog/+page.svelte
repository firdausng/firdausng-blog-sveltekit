<script lang="ts">
	import type { PageServerData } from './$types';

	export let data: PageServerData;
</script>

<div class="container mx-auto">
	<div class="flex flex-col gap-4 p-2">
		{#each data.posts as post}
			<div class="p-2 bg-app-dark dark:bg-app-light text-app-light dark:text-app-dark rounded shadow-inner shadow-app-lightest/50 dark:shadow-app-darkest/50">
				<a href={`blog/${post.slug}`}>
					<div>
						<p>{post.title}</p>
						<p>{new Date(post.date).toLocaleDateString()}</p>
					</div>
				</a>
			</div>
		{/each}
	</div>

</div>