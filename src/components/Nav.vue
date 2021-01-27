<template>
	<nav class="navbar navbar-expand-lg">
		<a class="navbar-brand" href="/">Tier 1 Laser</a>
		<button
			class="navbar-toggler"
			type="button"
			data-toggle="collapse"
			data-target="#navbarText"
			aria-controls="navbarText"
			aria-expanded="false"
			aria-label="Toggle navigation"
		>
			<span class="navbar-toggler-icon"></span>
		</button>
		<div class="collapse navbar-collapse" id="navbarText">
			<ul class="navbar-nav ml-auto">
				<li class="nav-item active">
					<a class="nav-link" href="#top">
						Home
						<span class="sr-only">(current)</span>
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#about">About</a>
				</li>
				<li>
					<a class="nav-link" href="#products">Portfolio</a>
				</li>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");

.navbar-brand {
	font-family: "Lobster", cursive;
	color: #ccffcb;
}
.navbar {
	position: fixed;
	width: 100%;
	top: 0;
	z-index: 1;
	background-color: #1c3144;
	box-shadow: 2px 2px 2px #de7c5a;
}
.nav-link {
	font-family: "Lobster", cursive;
	color: #ccffcb;
}
.nav-link:hover {
	color: #de7c5a;
}
.navbar-brand:hover {
	color: #de7c5a;
}
</style>
