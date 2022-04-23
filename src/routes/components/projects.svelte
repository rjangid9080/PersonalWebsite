<script>
	const projects = [
		{
			title: 'Geektrust/admin_UI',
			description: `He has developed a working interface for admins to see and delete users, using React JS and tailwind CSS. The users provided via an API. `,
			link: 'rjangid9080-geektrust-admin-ui.netlify.app/',
			repo: 'geektrust-admin-ui'
		},
		{
			title: 'Share Me',
			description: `He has developed Share Me social site using ReactJs, Sanity, and Google Authentication where you can collect and share images of anything which you find interesting`,
			link: 'sharemerj.netlify.app',
			repo: 'share-me'
		},
		{
			title: 'CRUD Application',
			description: `He has created Crud Application using SvelteKit as a frontend , NodeJS for server, ExpressJs as a backend framework , and MongoDB as Database.`,
			link: 'crud-app-using-svelte.vercel.app/',
			repo: 'crudAppUsingSvelte'
		},
		{
			title: 'JavaScript Projects',
			description: `He has developed some DOM manipulation projects using HTML,CSS,JavaScript.`,
			link: 'rjangid9080.github.io/Portfolio/#Projects',
			repo: 'JS-projects'
		}
	];
</script>

<!--Projects-->
<section class="w-full flex">
	<div class=" w-full p-4">
		<div class="self-center">
			<h1 class="text-center text-3xl text-gray-700">Projects</h1>
		</div>
		{#each projects as { title, description, link, repo }}
			<div class="w-full flex flex-col mt-12">
				<div class="w-full sm:w-1/2 self-center rounded shadow">
					<h1 class="p-2 text-center sil font-semibold text-gray-700 text-xl">{title}</h1>
					<p class="p-2 text-center text-gray-700 text-sm font-semibold">
						{description}
					</p>
					<div class="w-full flex flex-row justify-between">
						<a
							class="p-2 bg-blue-50 rounded shadow-md text-sm font-semibold text-gray-700 hover:bg-blue-100"
							href="https://{link}"
							target="_blank">Live Project</a
						>
						<a
							class="p-2 bg-amber-50 rounded shadow-md text-sm font-semibold text-gray-700 hover:bg-amber-100"
							href="https://github.com/rjangid9080/{repo}"
							target="_blank">Github Repo</a
						>
					</div>
				</div>
			</div>
		{/each}
	</div>
</section>

<!--End of Projects-->
<style>
	@import url('https://fonts.googleapis.com/css2?family=Shadows+Into+Light&display=swap');
	.sil {
		font-family: 'Shadows Into Light', cursive;
	}
</style>
