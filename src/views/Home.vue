<template>
	<div id="top">
		<div class="imgBox">
			<div class="title">Tier 1 Laser Engraving</div>
			<h2 class="title">Custom laser engraving solutions</h2>
			<div class="buttonContainer">
				<button onClick="window.location.href = '#contactForm'">
					Request a quote
				</button>
				<button onClick="window.location.href = '#products'">
					View Portfolio
				</button>
			</div>
		</div>
		<b-container fluid>
			<div class="contact">
				<b-row>
					<b-col class="box">
						<div class="individualItems">
							Contact Us <b-icon icon="chat-text-fill" animation="fade" />
						</div>
						<ul>
							<li>(828)-493-9650</li>
							<li>help@tier1laser.com</li>
						</ul>
					</b-col>
					<b-col class="box">
						<div class="individualItems">
							Hours <b-icon icon="clock" animation="spin" />
						</div>
						<ul>
							<li>Monday-Friday 9am-5pm(EST)</li>
						</ul>
					</b-col>
					<b-col class="box">
						<div class="individualItems">
							Services <b-icon icon="hammer" animation="cylon" />
						</div>

						<ul>
							<li>
								We offer a wide range of etching, engraving, and cutting
								services for most* materials. We also offer laser stippling for
								firearms.
							</li>
						</ul>
						<p class="disclaimer">
							*Due to our current equipment limitations, we can only etch metal,
							not cut or engrave it.*
						</p>
					</b-col>
				</b-row>
			</div>
		</b-container>

		<!-- about section here -->
		<div id="about">
			<b-card title="About" class="card">
				<div class="cardText">
					<b-card-text>
						We are a custom laser engraving, cutting, and etching operation. We
						accept custom work as well as sell ready-to-order items that are
						available on our selling platforms listed in the products section.
						Reach out today to get a quote on a custom order!
					</b-card-text>
				</div>
				<div class="cardlink-container">
					<a href="#" class="card-link">Contact Us</a>
					<b-link href="#" class="card-link">View Products for sale</b-link>
				</div>
			</b-card>
		</div>
		<!-- product section here -->
		<div id="products">
			<div class="products-container">
				<h4>Portfolio</h4>
				<div class="carousel-container">
					<!-- Text slides with image -->
					<b-icon icon="arrow-left" />
					<img class="gun" src="../assets/1.jpg" />

					<img class="gun" src="../assets/2.jpg" />
					<b-icon icon="arrow-right" />
				</div>
			</div>
		</div>

		<div id="contactForm">
			<div class="form-container">
				<h4>
					Contact Us
				</h4>
				<br />
				<input placeholder=" Name" /> <input placeholder=" Email" /><br />
				<textarea name=" Message" placeholder="message"></textarea><br /><br />
				<button onClick="submit">Submit</button>
			</div>

			<div class="footer">
				© Tier 1 Laser {{ new Date().getFullYear() }} <br />
				Built with <b-icon icon="heart-fill" /> by HerronDesigns
				<div class="social-container">
					Follow us
					<b-icon class="social-icon" icon="facebook" />
					<b-icon class="social-icon" icon="instagram" />
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.contact {
	font-weight: bold;
	font-size: 20px;
}
.gun {
	margin-top: 10px;
	margin-right: 10px;
	margin-left: 10px;
	height: 400px;
	width: 400px;
}
.carousel-container {
	width: 75%;
	height: auto;
	top: 25%;
	margin-left: auto;
	margin-right: auto;
}
.box {
	outline-style: solid;
	outline-width: thin;
	color: #27435c;
	background-color: #1c3144;
}
#contactForm {
	height: auto;
	background-color: #27435c;
}

.cardText {
	width: 80%;
	margin-left: auto;
	margin-right: auto;
	font-size: 19px;
}
.cardlink-container {
	margin-top: 20px;
}
.disclaimer {
	color: #889696;
	font-size: 12px;
	text-align: center;
}
.footer {
	color: #ccffcb;
	border-top-style: groove;
}
.form-container {
	text-align: center;
	padding-top: 50px;
	padding-bottom: 50px;
	color: #ccffcb;
}
.individualItems {
	color: #ccffcb;
}
.sk {
	width: 100% !important;
	height: 80vh !important;
}
.social-icon {
	margin-right: 5px;
}
input {
	font-size: 20px;
	border-top-style: hidden;
	border-right-style: hidden;
	border-left-style: hidden;
	border-bottom-style: groove;
	background-color: transparent;

	margin-right: 20px;
}

textarea {
	font-size: 20px;
	margin-top: 20px;
	border-top-style: hidden;
	border-right-style: hidden;
	border-left-style: hidden;
	border-bottom-style: groove;
	background-color: transparent;
}
ul {
	list-style-type: none;
	text-align: center;
	font-size: 18px;
	color: #ccffcb;
}
.card-link {
	font-size: 19px;
}
.imgBox {
	background-image: url("../assets/laser-4398314_1280.jpg");
	width: 100%;
	height: 82vh;
	background-size: cover;
	background-repeat: no-repeat;
}
.title {
	font-size: 50px;
	text-align: center;
	position: relative;
	top: 35%;
	color: #ccffcb;
	opacity: 0.75;
	text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000,
		1px 1px 0 #000;
}
.social-container {
	color: #ccffcb;
	margin-left: 80%;
}
.buttonContainer {
	position: relative;
	top: 50%;
}
button {
	margin-right: 15px;
	width: 150px;
	height: 50px;
	font-size: 18px;

	background-image: linear-gradient(to right, #ccffcb, #254058);

	border-top-right-radius: 10px;

	border-bottom-left-radius: 10px;
}
button:hover {
	color: #de7c5a;
}
#about {
	height: auto;
	margin-top: 3px;
	padding-top: 50px;
	outline-style: solid;
	outline-width: thin;
	outline-color: #27435c;
	color: #ccffcb;
}
#products {
	height: auto;
	padding-bottom: 50px;
	padding-top: 60px;
	margin-top: 3px;
	color: #ccffcb;
}
.card {
	height: auto;
	background-color: #254058;
}
</style>

<script>
export default {
	data() {
		return {
			slide: 0,
			sliding: null,
		};
	},

	methods: {
		onSlideStart() {
			this.sliding = true;
		},
		onSlideEnd() {
			this.sliding = false;
		},
	},
};
</script>
