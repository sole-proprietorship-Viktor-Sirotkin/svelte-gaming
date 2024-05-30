<script>
	import Title from "$lib/Title.svelte";
</script>

<main>
    <Title title="Svelte Gaming - Home" />
	<div class="index">
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe eum nesciunt provident minus
			dicta ad itaque aperiam odit fuga architecto quos enim tenetur voluptatem beatae quod cumque
			facere expedita, id repellendus voluptatibus. Officiis eligendi voluptate a porro! Minus
			veniam suscipit rerum laboriosam, distinctio tenetur. Ex quia expedita temporibus nihil eos?
		</p>

		<!-- <button on:click={changeTitle}>Change Title</button> -->
		<!-- <input type="text" bind:value={title}> -->
	</div>
</main>

<style>
	.index {
		display: block;
		margin: 20px auto;
	}
</style>
