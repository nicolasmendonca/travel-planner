<script>
	import Sidebar from '$lib/components/Sidebar.svelte';

	import '../tailwind.css';
</script>

<div class="bg-gray-900 min-h-screen text-gray-100">
	<div class="grid grid-cols-6 grid-rows-1 gap-4 py-8 px-6">
		<div class="col-span-6 md:col-span-2">
			<Sidebar />
		</div>
		<div class="col-span-6 md:col-span-4">
			<slot />
		</div>
	</div>
</div>
