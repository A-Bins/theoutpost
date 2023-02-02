<script lang="ts">
</script>

<main>
		<div class="menubar bg(#FFFFFF)">
			<!-- <a href="https://discord.gg/r9pMV9kHAy" target="_blank" rel="noreferrer"> -->
				<img src="/copied_icon_40px.png" class="logo" alt="logo" />
			<!-- </a>	 -->
		</div>
	<h1 class="relative top(100px)">The Outpost</h1>

	<!-- <div class="card"> -->
		<!-- <Counter /> -->
	<!-- </div> -->

</main>

<style>
	.menubar { 
		filter: drop-shadow(0 0 2em #000000);
		position: relative;
  	top: 0;
		/* background: #000; */
  	left: 0;
  	right: 0;
		height: 50px;
		width: 100%;
		display: flex;
		color: aqua;
		align-items: center;
		justify-content: space-around;
	}
	.logo {
		height: 60px;
		position: absolute;
		top: 20px;
		/* 최상단으로부터 20px 떨어져있음 */
		/* bottom: 300px; */

		/* will-change: filter; */
	}
	.logo:hover {
		filter: drop-shadow(0 0 1em #a0a0a0);
	}
	/* .click-to-discord {
		color: #888;
	} */
</style>