<script>
	export let name;
</script>

<div class="h-screen flex justify-center items-center">
	<div class="poker_table rounded-full w-4/5 h-4/6 border border-black" />
</div>

<style lang="postcss" global>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;

	.poker_table {
		background-color: #35654d;
		border: 20px solid black;
		background: radial-gradient(#52c234, #061700);
	}
</style>
