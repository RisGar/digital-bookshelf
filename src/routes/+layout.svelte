<script>
	import '../app.css'
</script>

<div class="bg-neutral text-neutral-content">
	<div class="max-w-xl mx-auto navbar">
		<div class="navbar-start">
			<a href="/" class="btn btn-ghost text-xl">digital-bookshelf</a>
		</div>
	</div>
</div>

<div class="max-w-xl mx-auto py-8 px-4">
	<slot />
</div>

<footer>
	<p>&copy; {new Date().getFullYear()} Rishab Garg</p>
</footer>
