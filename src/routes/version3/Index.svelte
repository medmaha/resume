<script>
	import Header from './Header.svelte';
	import SocialLinks from './SocialLinks.svelte';
	import Summary from './Summary.svelte';
	import Skills from './Skills.svelte';
	import Experiance from './Experiance.svelte';
	import Contacts from './Contacts.svelte';
</script>

<Header />
<SocialLinks />

<main class="max-w-[900px] w-full space-y-6 py-4">
	<section class="w-full">
		<Summary />
	</section>
	<section class="w-full">
		<Skills />
	</section>
	<section class="w-full">
		<Experiance />
	</section>
	<section class="w-full">
		<Contacts />
	</section>
</main>
