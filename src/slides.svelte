<script lang="ts">
	import { Presentation, Slide, Code } from '@components'
	import { signal } from '@motion'

	const circle = signal(
		{ x: 0, y: 200, r: 80, fill: '#00ffff' },
		{ duration: 2000 }
	)
</script>

<Presentation>
	<Slide animate>
		<p class="font-bold text-8xl">🪄 Animotion</p>
	</Slide>
</Presentation>
