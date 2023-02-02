<script lang="ts">
</script>

<main>
		<div class="menubar">
			<img src="/copied_icon_40px.png" class="logo" alt="logo" />
		<!-- <a href="https://vitejs.dev" target="_blank" rel="noreferrer">  -->
					
		<!-- </a> -->
		</div>
	<h1 >The Outpost</h1>

	<!-- <div class="card"> -->
		<!-- <Counter /> -->
	<!-- </div> -->

</main>

<style>
	.menubar { 
		position: relative;
  	top: 0;
  	left: 0;
  	right: 0;
		height: 60px;
		width: 100%;
		display: flex;
		color: aqua;
		align-items: center;
		justify-content: space-around;
	}
	.logo {
		height: 50px;
		position: absolute;
		/* 최상단으로부터 20px 떨어져있음 */
		/* bottom: 300px; */

		will-change: filter;
	}
	.logo:hover {
		filter: drop-shadow(0 0 2em #646cffaa);
	}
	/* .click-to-discord {
		color: #888;
	} */
</style>