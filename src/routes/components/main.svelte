<script>
	import Social from './social.svelte';
	import Icon from '@iconify/svelte';
	import * as animateScroll from 'svelte-scrollto';

	let mainContainterHeight;

	function scrollToAbout(){
		animateScroll.scrollTo({offset:mainContainterHeight-64})
	}
</script>

<!--Main-->
<section bind:clientHeight={mainContainterHeight} class="w-full h-screen flex flex-row items-center p-4">
    <div class="w-11/12 width absolute">
        <div class="h-36 sm:h-40 bg-blue-600  rounded-md opacity-10 origin-center -rotate-6" />
        <div class="h-36 sm:h-40 bg-amber-500 rounded-md opacity-10 origin-bottom rotate-6 -translate-x-4"/>
    </div>
	<div class="z-20 w-1/5">
		<Social />
	</div>
	<div class="z-10 w-4/5">
		<span class="w-1/2 self-center">
			<p class=" text-3xl sm:text-4xl sil font-semibold text-gray-700">Hey ! This is Rohit Jangid</p>
			<p class="pt-4 pb-4 font-semibold text-gray-700">and looking forward to work as a full stack developer. <br> And promising that if you give him a chance then definitely <br> he gives you better results.</p>
			<button on:click={scrollToAbout}
				class=" self-center shadow bg-blue-500 rounded text-white hover:bg-blue-600 p-2 text-xs font-semibold"
				>Know him ?</button
			>
		</span>
	</div>
	<div class="absolute right-1/2 top">
		<Icon class="animate-bounce text-3xl text-blue-400" icon="bi:arrow-down" inline={true} />
	</div>
</section>

<!--End Main-->
<style>
	@import url('https://fonts.googleapis.com/css2?family=Shadows+Into+Light&display=swap');
	.sil {
		font-family: 'Shadows Into Light', cursive;
	}
	.top {
		top: 90%;
	}
    @media screen and (min-width:860px){
        .width{
            width: 98%;
        }
    }
</style>
