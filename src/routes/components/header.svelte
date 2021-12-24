<script>
	import * as animateScroll from 'svelte-scrollto';
</script>

<!--NavBar-->
<section class="w-full z-50 flex flex-row justify-between p-4 bg-white
 sm:pr-12 sm:pl-12 fixed overflow-hidden ">
	<div on:click={()=>animateScroll.scrollToTop()} class="flex hover:cursor-pointer">
		<span class="h-8 w-8 bg-blue-600 rounded-md opacity-60 origin-center rotate-6" />
		<span class="h-8 w-8 bg-amber-500 rounded-md origin-bottom -rotate-12 -translate-x-4">
			<p class="rotate-12 text-white text-center text-xl -translate-y-1 lowercase pacifico">
				RJ
			</p>
		</span>
	</div>
	<div class="flex space-x-6">
		<span class="hover:cursor-pointer font-semibold text-gray-600 hover:text-gray-900">Resume</span>
		<span on:click={()=>animateScroll.scrollToBottom()} class="hover:cursor-pointer font-semibold text-gray-600 hover:text-gray-900">Contact</span>
	</div>
</section>
<!--End of NavBar-->
<style>
	@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
    .pacifico{
        font-family: 'Pacifico',cursive;
    }
</style>
