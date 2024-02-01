<script lang="ts">
	// @ts-ignore
	import Masonry from 'masonry-layout';
	import { onMount } from 'svelte';

	onMount(() => {
		// vanilla JS
		// init with element
		const grid = document.querySelector('.grid-1') as HTMLElement;
		const msnry = new Masonry(grid, {
			itemSelector: '.grid-item'
		});

		window.addEventListener('resize', () => {
			if (msnry.masonry) msnry.masonry('layout', undefined);
		});
	});
</script>

<div class="grid-1">
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
	<div
		class="grid-item float-left w-[100%] sm:w-[calc(100%/2)] md:w-[calc(100%/3)] lg:w-[calc(100%/4)] p-5"
	>
		<div class="bg-blue-500 h-10">하하</div>
	</div>
</div>
