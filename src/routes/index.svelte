<script>
	import Card from '../lib/components/Card.svelte';
</script>

<Card>
	<h1 class="text-2xl font-bold m-2">Vuelos</h1>

	<fieldset>
		<legend>Agregar un vuelo</legend>
		<div class="my-4 grid gap-6 mb-6 lg:grid-cols-2">
			<div>
				<label
					for="flightId"
					class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
					>ID del vuelo</label
				>
				<input
					id="flightId"
					type="text"
					placeholder="ABC1234"
					class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
				/>
			</div>
			<div>
				<div class="relative">
					<div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
						<svg
							class="w-5 h-5 text-gray-500 dark:text-gray-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
								clip-rule="evenodd"
							/></svg
						>
					</div>
					<input
						datepicker
						type="text"
						class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
						placeholder="Select date"
					/>
				</div>
			</div>
		</div>
	</fieldset>
</Card>
