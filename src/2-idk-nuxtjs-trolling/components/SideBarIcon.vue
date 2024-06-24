<template>
	<div class="sidebar-icon group">
		<Icon :name="icon" color="black" class="w-8 h-8" />

		<span class="sidebar-tooltip group-hover:scale-100">
			{{ title }}
		</span>
	</div>
</template>

<script>
	export default {
		props: {
			title: {
				type: String,
				required: true
			},
			icon: {
				type: String,
				required: true
			}
		}
	}

</script>