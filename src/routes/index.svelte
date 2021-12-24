<script>
	import About from './components/about.svelte';
	import Header from './components/header.svelte';
	import Footer from './components/footer.svelte';
	import Main from './components/main.svelte'
	import Projects from './components/projects.svelte';
</script>

<div class="w-full">
	<Header />
	<Main/>
	<About />
	<Projects/>
	<Footer/>
</div>
<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
