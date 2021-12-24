<script>
	import Icon from '@iconify/svelte';
	import * as animateScroll from 'svelte-scrollto';

    const date = new Date()
    let year = date.getFullYear();
</script>

<!--Footer-->
<section class="w-full flex flex-col divide-y justify-center bg-amber-50">
	<div class="w-3/4 pt-12 pb-12 self-center">
		<div class="flex flex-col sm:flex-row justify-between">
			<div class="sm:self-center">
                <ul>
                    <li class="font-semibold text-gray-700">Rohit Jangid</li>
                    <li class="font-semibold text-gray-700">+91-7610832827</li>
                    <li class="font-semibold text-gray-700">rohit.jangid2433@gmail.com</li>
                </ul>
            </div>
			<!--Social Links-->
			<div class="sm:self-center">
				<ul class="flex">
					<li class="p-2 ">
						<a href="https://www.linkedin.com/in/rohit-jangid-250893189/" target="_blank" class="p-1 text-2xl text-gray-700 hover:text-gray-900 "><Icon icon="fa-brands:linkedin-in" inline={true} /></a>
					</li>
					<li class="p-2">
						<a href="https://github.com/rjangid9080" target="_blank" class="p-1 text-2xl text-gray-700 hover:text-gray-900"><Icon icon="akar-icons:github-fill" inline={true} /></a
						>
					</li>
					<!-- <li class="p-2">
						<a href="https://www.twitter.com/_rjangid_/" target="_blank" class="p-1 text-2xl text-gray-700 hover:text-gray-900"><Icon icon="bi:twitter" inline={true} /></a>
					</li>
					<li class="p-2">
						<a href="https://www.instagram.com/_r.jangid_/" target="_blank" class="p-1 text-2xl text-gray-700 hover:text-gray-900"><Icon icon="bi:instagram" inline={true} /></a>
					</li> -->
				</ul>
			</div>
		</div>
	</div>
	<div class="w-3/4 self-center pt-4 pb-4">
        <p class="text-sm text-center font-semibold text-gray-700">&copy; copyright {year}. Made by <a href="/" on:click={()=>animateScroll.scrollToTop()} class="underline hover:text-gray-900">Rohit Jangid</a> with Sveltekit</p>
    </div>
</section>
<!--End Footer-->
