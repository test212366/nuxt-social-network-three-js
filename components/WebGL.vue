
<script setup lang="ts">

	import { WebGLScene } from '../class/WebGL'
 
	const AimWebGL: Ref<HTMLCanvasElement | null> = ref(null)

	onMounted(() => {
		new WebGLScene({
			dom: AimWebGL.value 
		})
	})
 
	
</script>

<template> 
	<div ref="AimWebGL">

	</div>
</template>