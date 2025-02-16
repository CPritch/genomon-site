<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="navbar bg-base-100 shadow-sm">
	<div class="flex-0">
	  <a href="/" class="btn btn-ghost text-xl">Genomon</a>
	</div>
	<div class="flex-none">
	  <ul class="menu menu-horizontal px-1">
		<li>
		  <details>
			<summary>Tools</summary>
			<ul class="bg-base-100 rounded-t-none p-2">
			  <li><a href="/card-management">Card Management</a></li>
			</ul>
		  </details>
		</li>
	  </ul>
	</div>
  </div>
{@render children()}
