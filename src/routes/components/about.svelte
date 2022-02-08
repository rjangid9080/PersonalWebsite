<script>
	import Icon from '@iconify/svelte';
</script>

<!--About Section-->
<section class="flex flex-col sm:flex-row w-full p-4">
	<div class="w-full sm:w-1/2 flex flex-col">
		<div class="self-center flex flex-col">
			<div class="self-center flex flex-col">
				<h1 class="font-semibold text-xl text-gray-700">About Him !</h1>
				<span class="h-1 bg-blue-400 rounded-full" />
			</div>
			<div class="p-3">
				<p class="pt-4 sm:pt-3 sm:pr-3 sm:pl-3 text-gray-700">
					Currently, He doesn't have any industry experience. But excited to be a part of this
					industry.
				</p>
				<p class="pt-4 sm:pt-3 sm:pr-3 sm:pl-3 text-gray-700">
					You can check his <b>skills</b> section and some work on his
					<b>project</b> section.
				</p>
				<p class="pt-4 sm:pt-3 sm:pr-3 sm:pl-3 text-gray-700">
					He is looking forward to Job opportunities where he can contribute, learn and grow. If you
					have a good opportunity that matches his skills and experience then don't hesitate to <b
						>contact</b
					> him.
				</p>
			</div>
		</div>
	</div>
	<div class="w-full sm:w-1/2 flex flex-col">
		<div class="self-center flex flex-col pb-4">
			<h1 class="font-semibold text-xl text-gray-700">Skills</h1>
			<span class="h-1 bg-amber-500 rounded-full" />
		</div>
		<div class="grid grid-cols-2 md:grid-cols-3 gap-3">
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="vscode-icons:file-type-html" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">HTML</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="vscode-icons:file-type-css" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">CSS</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="logos:javascript" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">JavaScript</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="logos:svelte-icon" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">SvelteKit</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="logos:tailwindcss-icon" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">TailwindCSS</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="vscode-icons:file-type-reactjs" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">ReactJS</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="logos:nodejs" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">Node JS</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="simple-icons:express" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">Express JS</p>
			</div>
			<div
				class="p-2 sm:w-36 lg:w-40 flex flex-col sm:flex-row justify-center bg-slate-200 border-2 rounded-md shadow"
			>
				<span class="self-center text-gray-600">
					<Icon icon="vscode-icons:file-type-mongo" inline={true} />
				</span>
				<p class="self-center text-gray-600 pl-2 font-semibold">MongoDB</p>
			</div>
		</div>
	</div>
</section>
<!--End About Section-->
