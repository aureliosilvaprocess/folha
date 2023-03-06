<script>
	import '../app.postcss';
</script>

<div class="p-10">
	<h1 class="text-4xl text-white font-bold pb-2">Controle de horas</h1>
	<hr />
	<slot />
</div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.slate.900);
	}
</style>
