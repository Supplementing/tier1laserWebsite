<template>
	<div id="app">
		<Nav />
		<router-view />
	</div>
</template>
<script>
import Nav from "../src/components/Nav";
export default {
	components: {
		Nav,
	},
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");
#app {
	width: 100%;
	height: 100%;
	background-color: #1c3144;

	font-family: "Lobster", cursive;

	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}
p {
	text-align: left;
}
#nav {
	padding: 30px;

	background-color: #1c3144;
	text-align: right;

	width: 100%;

	height: 30px;
	box-shadow: 122px blue;
}
.logo {
	color: lightblue;
	text-align: left;
}
#nav a {
	font-weight: bold;
	color: #889696;
}

#nav a.router-link-exact-active {
	color: red;
}
</style>
