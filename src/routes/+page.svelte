<script lang="ts">
	import "@home/styles";

	import { Button, SEO } from "@sharing/atoms";
</script>

<SEO title="Home" />

<section class="home">
	<h1>tfverse CLI</h1>

	<h3>Built-in components</h3>
	<p>Buttons</p>
	<div>
		<p>Normal</p>
		<Button text="Example text" />
		<p>Gradient</p>
		<Button
			text="Example text"
			config={{
				style: "gradient",
			}}
		/>
		<p>Outline</p>
		<Button
			text="Example text"
			config={{
				style: "outline",
			}}
		/>
		<p>Invert</p>
		<Button
			text="Example text"
			config={{
				style: "invert",
			}}
		/>
	</div>
</section>
