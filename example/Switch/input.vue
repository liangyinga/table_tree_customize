<template>
	<div>
		<Input v-model="value"  style="width: 200px" />
		<!-- <span>{{value}}</span> -->
	</div>
</template>
<script>
	export default{
		name: 'ly-input',
		data(){
			return{
				value:'sss'
			}
		},
		mounted(){
			// this.value = "dddd"
		}
	}
</script>