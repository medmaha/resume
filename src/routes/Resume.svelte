
<script>
	import ContactDetails from "./ContactDetails.svelte";
	import Education from "./Education.svelte";
	import Experience from "./Experience.svelte";
	import Header from "./Header.svelte";
	import SkillsInterest from "./Skills&Interest.svelte";    

</script>

<div class="p-6 sm:p-2 flex justify-center">
    <div class="max-w-[900px] block w-full mx-auto">
        <Header/>
        <ContactDetails/>
        <Experience/>
        <Education/>
        <SkillsInterest/>
    </div>
</div>
