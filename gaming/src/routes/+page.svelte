<script>
    let title = 'New Title for Gaming';

    const changeTitle = () => {
        title = 'Title Changed';
    }
</script>

<main>
	<div class="index">
		<h2>{title}</h2>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe eum nesciunt provident minus
			dicta ad itaque aperiam odit fuga architecto quos enim tenetur voluptatem beatae quod cumque
			facere expedita, id repellendus voluptatibus. Officiis eligendi voluptate a porro! Minus
			veniam suscipit rerum laboriosam, distinctio tenetur. Ex quia expedita temporibus nihil eos?
		</p>

        <button on:click={changeTitle}>Change Title</button>
        <input type="text" bind:value={title}>
	</div>
</main>

<style>
    .index {
        display: block;
        text-align: center;
        margin: 20px auto;
    }
</style>
