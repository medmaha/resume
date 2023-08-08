<script>
	const skills = [
		'GIT',
		'Python',
		'Javascrip',
		'Django',
		'React',
		'Node',
		'Express',
		'SocketIO',
		'NextJs',
		'Sveltekit',
		'VueJs',
		'AngularJs',
		'Firebase',
		'Postgresql',
		'MongoDB',
		'Flask',
		'Redis',
		'Redux',
		'HTML',
		'CSS',
		'and More..'
	];
</script>

<h2 class="subheading pb-4 flex w-full items-end gap-1">
	<span class="leading-none font-semibold text-lg">Skills</span>
	<span class="inline-block h-[1px] flex-1 bg-black w-full mb-1" />
</h2>
<div class="flex flex-wrap pl-10 gap-1">
	{#each skills as skill, i}
		<span class="skill text-gray-700 text-sm">{skill}</span>
		{#if skill !== skills[skills.length - 1]}
			<span class="pt-0.5">-</span>
		{/if}
	{/each}
</div>

<style>
	.skill {
		padding: 5px 10px;
	}
</style>
