<nav>
	<a href=".">Home</a>
	<a href="/about">About</a>
	<a href="/settings">Settings</a>
</nav>

<slot></slot>

<style>
	:root {
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
			'Open Sans', 'Helvetica Neue', sans-serif;
	}

	:global(main) {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

	:global(h1) {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4rem;
		font-weight: 100;
		line-height: 1.1;
		margin: 4rem auto;
		max-width: 14rem;
	}

	:global(p) {
		max-width: 14rem;
		margin: 2rem auto;
		line-height: 1.35;
	}

	@media (min-width: 480px) {
		:global(h1)  {
			max-width: none;
		}

		:global(p) {
			max-width: none;
		}
	}
</style>
