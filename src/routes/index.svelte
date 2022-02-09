<script>
	import CarbonTracker from '../../examples/data/0/App.svelte';
	import Examples from '../../examples/data/index.svelte';
</script>

<svelte:head>
	<title>Pancake • Charts for Svelte apps</title>
</svelte:head>

<header>
	<h1>
		Bundle Pancake analytics
		<small>custom teams tackling your data science problems </small>
	</h1>

	<p>
		bundle will help you to get your engineering dream team.
	</p>

	<p>
		Unlike most freelance companies out there, bundle is designed with objective of solve all your design, development and deploy problems in one step.
		<a
			href="https://dev.to/richharris/a-new-technique-for-making-responsive-javascript-free-charts-gmp"
			>Here's how.</a
		>
	</p>
</header>

<section class="hero">
	<CarbonTracker />
</section>

<section>
	<h2>Usage</h2>
	<p>Documentation is TODO. In the meantime, here are some examples:</p>
</section>

<section class="examples">
	<h2>Examples</h2>
	<div class="chart-grid">
		<Examples />
	</div>
</section>

<style>
	header {
		max-width: 56rem;
		margin: 0 auto;
	}

	.hero {
		margin: 0 auto 4em auto;
		max-width: 80em;
	}

	section {
		max-width: 56em;
		margin: 0 auto 4em auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: lowercase;
		font-weight: 400;
		margin: 0 0 0.5em 0;
	}

	small {
		color: #999;
		font-size: 0.5em;
		display: block;
	}

	.examples {
		max-width: 56rem;
		margin: 0 auto;
	}

	h2 {
		font-size: 2em;
	}

	/* .chart-grid {
		display: grid;
		grid-column-gap: 3em;
		grid-row-gap: 1em;
	} */

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}

	@media (min-width: 960px) {
		/* .chart-grid {
			grid-template-columns: repeat(2, 1fr);
		} */
	}
</style>
