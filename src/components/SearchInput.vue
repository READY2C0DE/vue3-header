<template>
	<div class="bg-gray-100 w-2/6 lg:w-2/5 hidden sm:flex items-center justify-between ">
		<input type="text" placeholder="Поиск по сайту..."
			class="bg-gray-100 text-lg outline-none text-gray-600 p-4 w-full rounded">
		<img src="../assets/search.png" class="p-4 border-l-2 lg:block hidden" alt="">
	</div>
</template>

<script>
export default {
	name: 'SearchInput',
}
</script>