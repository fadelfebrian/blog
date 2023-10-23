<script lang="ts">
	import * as config from '$lib/config'
	import { Heart } from 'lucide-svelte'

</script>

<!-- Footer -->
<footer>
	<p>{config.footerdesc} <Heart color="#e60000" /> {new Date().getFullYear()}</p>
</footer>

<style>
	footer {
		padding-block: var(--size-7);
		border-top: 1px solid var(--border);
	}

	p {
		display: flex;
		gap: 0.2rem;
		color: var(--text-2);
	}
</style>
