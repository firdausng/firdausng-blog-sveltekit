<script lang="ts">

	function ToogleDarkMode(){
		if (localStorage.theme === 'dark' || (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
			document.documentElement.classList.add('dark')
			localStorage.theme = 'light'
		} else {
			document.documentElement.classList.remove('dark')
			localStorage.theme = 'dark'
		}
	}
</script>
<aside class="p-2 w-48">
	<button on:click={ToogleDarkMode}>Toogle Dark Mode</button>
	<ul class="flex flex-col gap-2 p-2">
		<li>
			<a href="/">Home</a>
		</li>
		<li>
			<a href="/blog">Blog</a>

		</li>
<!--		<li>-->
<!--			<a href="/work">Work</a>-->
<!--		</li>-->
<!--		<li>-->
<!--			<a href="/about">About</a>-->
<!--		</li>-->

	</ul>
</aside>