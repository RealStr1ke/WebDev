<template>
	<div class="fixed top-0 left-0 h-screen w-16 flex flex-col bg-discord-900 text-white">
		<SideBarIcon icon="mdi:home" title="Home"/>
		<div class="sidebar-hr"></div>
		<SideBarIcon icon="mdi:github" title="GitHub"/>
		<SideBarIcon icon="mdi:discord" title="Discord"/>
		<SideBarIcon icon="mdi:reddit" title="Reddit"/>
		<SideBarIcon icon="mdi:youtube" title="Youtube"/>
		<SideBarIcon icon="mdi:email" title="Email"/>
	</div>
</template>

<script>
const SideBarIcon = () => import('@/components/SideBarIcon.vue')

export default {
	components: {
		SideBarIcon
	}
}
</script>