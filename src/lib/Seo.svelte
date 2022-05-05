<script>
	export let title = null;
	let assembledTitle = title ? `${title} | Ben Altair Ingham` : 'Ben Altair Ingham';
</script>

<svelte:head>
	<title>{assembledTitle}</title>
</svelte:head>

<!-- TODO: Import Svelte SEO library to fill this component out with more features (social, etc) -->
