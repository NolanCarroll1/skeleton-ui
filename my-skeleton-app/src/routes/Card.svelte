<script>
	// @ts-ignore
	import MyButton from "./Button.svelte"
	// @ts-ignore
	import MyCheck from "./Checkbox.svelte"
	// @ts-ignore
	import MyInput from "./Input.svelte"
</script>

<div class="bg-gray-600 rounded-lg p-8 shadow max-md:">
	<form action="/auth" class="flex flex-col space-y-4">
	  <MyInput placeholder="Username"/>
		<MyInput placeholder="Password"/>
		<MyCheck/>
		<MyButton name="Login" type="regular"/>
	</form>
	
</div>