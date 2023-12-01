<script>
	// Importa la libreria svelte
	import { onMount } from 'svelte';

	// Funzione per eseguire operazioni dopo il mount del componente
	onMount(() => {
		// Esempio di operazione dopo il mount (opzionale)
	});
</script>

<div class="grid grid-cols-2 gap-4 h-screen p-4">
	<!-- Colonna di Sinistra -->
	<div class="flex flex-col h-full">
		<div class="bg-gray-200 p-4 mb-4 h-1/3">Elemento 1</div>
		<div class="bg-gray-200 p-4 h-full">Elemento 2</div>
	</div>

	<!-- Colonna di Destra -->
	<div class="h-full">
		<div class="bg-gray-200 p-4 h-full">Elemento 2</div>
	</div>
</div>

<style>
	/* Aggiungi eventuali personalizzazioni di stile qui */

	/* Per utilizzare Tailwind CSS, puoi anche aggiungere le classi direttamente nel file Svelte */
</style>
