<!-- page.svelte -->

<script>
	import '../styles/global.scss';
	import '../styles/page.scss';
	import Title from './Title.svelte';
	import About from './About.svelte';
	import Projects from './Projects.svelte';
	import Work from './Work.svelte';
	import Education from './Education.svelte';
	import Skills from './Skills.svelte';
	import Contact from './Contact.svelte';
	import Footer from './Footer.svelte';
</script>

<div class="container">
	<Title />

	<About />

	<div class="bar-two"></div>

	<Projects />

	<div class="bar-two"></div>

	<Work />

	<div class="bar-two"></div>

	<Education />

	<div class="bar-two"></div>

	<Skills />

	<div class="bar-two"></div>

	<Contact />
</div>

<Footer />
