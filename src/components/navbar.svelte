<script lang="ts" >

function toggle() {
	window.document.body.classList.toggle('dark')
}

// figure out why this doesnt work
/*
$:{ if (window.matchMedia('(prefers-color-scheme: dark)').matches) { 
		window.document.body.classList.add('dark')
	}
	else{
		window.document.body.classList.remove('dark')
	}
}
*/


	

</script>
<button on:click={toggle}>dark mode?</button>