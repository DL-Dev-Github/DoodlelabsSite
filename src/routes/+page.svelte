<script>
	import { onMount } from 'svelte';
	//import bgVideo from '$lib/images/front.mp4';
	import doodlelabslogosmall from '$lib/images/doodlelabssmall.png';
	import doodlelabslogobig from '$lib/images/doodlelabsbig.png';
	import doodlelabslogowhite from '$lib/images/doodlelabswhite.png';
	import twittericon from '$lib/images/twitter.png';
	import emailicon from '$lib/images/email.png';
	import discordicon from '$lib/images/discord.png';

	import mooksicon from '$lib/images/mooks.png';
	import slidericon from '$lib/images/slider.png';
	import neoicon from '$lib/images/neo.png';
	import agentsicon from '$lib/images/agents.png';
	import deciphericon from '$lib/images/decipher.png';
	import imicon from '$lib/images/im.png';
	import vistaicon from '$lib/images/vista.png';
	let offset = 0;
	onMount(() => {
		offset = window.pageYOffset;
	});
</script>

<svelte:head>
	<title>Doodle Labs - NFT Genart and Limited Editions</title>
	<meta name="description" content="Doodle Labs is an NFT genart company specializing in limited editions, crafted by talented artists and world-renowned brands. Explore the unique collection and own a piece of digital art today." />
	<meta name="keywords" content="Doodle Labs, NFT, Genart, Limited Editions, Digital Art, Unique Collection, Artist, Brands">
	<meta name="author" content="Doodle Labs">
	<meta name="robots" content="index, follow">
	<meta name="image" content={doodlelabslogobig}>
	<meta name="og:title" content="Doodle Labs - NFT Genart and Limited Editions">
	<meta name="og:description" content="Doodle Labs is an NFT genart company specializing in limited editions, crafted by talented artists and world-renowned brands. Explore the unique collection and own a piece of digital art today.">
	<meta name="og:image" content={doodlelabslogobig}>
	<meta name="og:url" content="https://doodlelabs.io">
	<meta name="og:site_name" content="Doodle Labs">
	<meta name="og:type" content="website">
	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:image" content={doodlelabslogobig}>
	<meta name="twitter:title" content="Doodle Labs - NFT Genart and Limited Editions">
	<meta name="twitter:description" content="Doodle Labs is an NFT genart company specializing in limited editions, crafted by talented artists and world-renowned brands. Explore the unique collection and own a piece of digital art today.">
</svelte:head>

<!--https://opensea.io/collection/vistas-by-anton-ermakov 
https://opensea.io/collection/agents-brown-and-knows-by-mr-kaves
https://opensea.io/collection/sliderverse-by-che-yu-wu-x-white-castle
https://opensea.io/collection/industrial-melanism-by-neil-grayson
https://opensea.io/collection/the-family-mooks-by-mr-kaves
https://opensea.io/collection/neogen-space-monkeys-by-dalek-x-generative-artwork
https://opensea.io/collection/deciphers-by-irene-mamiye
-->
<main><header class="site-header">
	<div class="logo-container">
		<img src={doodlelabslogosmall} alt="Doodle Labs" class="header-logo"/>
	</div>
</header>
<section class="hero">
	<div class="hero-text">
	
		<div class="hero-content">
			<h1 class="hero-title">Limited edition NFT drops from your favorite artists & brands</h1>
			<p class="hero-description">Experience and interact with the best artists & brands on the blockchain via art-driven collectibles.</p>
		</div>	<img src="{doodlelabslogobig}" alt="Doodle Labs" class="hero-logo" />
	</div>
	<div class="hero-decoration">
		<!-- Add decorative paths or SVGs here -->
	</div>
</section>


<section class="featured-projects">
	<h2 class="projects-title">Our Projects</h2>
	<div class="project-card">
		
			<img src="{mooksicon}" alt="Doodle Labs" class="project-image" />
		
		
		<div class="project-description">
			<h3>The Family Mooks by Mr. Kaves</h3>
			
			<p>Join the infamous Family Mooks on their misadventures through 1980’s Brokeland. Just remember, anything can happen under Mama’s spell...</p>
			<a href="https://opensea.io/collection/the-family-mooks-by-mr-kaves" class="primary-button-link">
				<button class="primary-button">View Collection</button>
			</a>
		</div>
	</div>
	<!-- Repeat .project-card for more projects -->
</section>
<section class="featured-projects">

	<div class="project-card">
		
			<img src="{slidericon}" alt="Doodle Labs" class="project-image" />
		
		
		<div class="project-description">
			<h3>Sliderverse
				by Che-Yu Wu
				</h3>
			<p>In honor of White Castle’s 100th Birthday, renowned multimedia artist Che-Yu Wu has reimagined the White Castle menu through a generative art lens.</p>
			<a href="https://opensea.io/collection/sliderverse-by-che-yu-wu-x-white-castle" class="primary-button-link">
				<button class="primary-button">View Collection</button>
			</a>
		</div>
	</div>
	<!-- Repeat .project-card for more projects -->
</section>
<section class="featured-projects">

	<div class="project-card">
		
			<img src="{neoicon}" alt="Doodle Labs" class="project-image" />
		
		
		<div class="project-description">
			<h3>Neogen Space Monkeys
				by Dalek x Generative Artworks
				
				</h3>
			<p>Neogen Space Monkeys is a groundbreaking collaboration merging the worlds of traditional and generative art.</p>
			<a href="https://opensea.io/collection/neogen-space-monkeys-by-dalek-x-generative-artwork" class="primary-button-link">
				<button class="primary-button">View Collection</button>
			</a>
		</div>
	</div>
	<!-- Repeat .project-card for more projects -->
</section>
<section class="featured-projects">

	<div class="project-card">
		
			<img src="{agentsicon}" alt="Doodle Labs" class="project-image" />
		
		
		<div class="project-description">
			<h3>Agents Brown & Knows
				by Mr. Kaves</h3>
			<p>
				
				Agents Brown & Knows are on the scene to apprehend The Family Mooks!</p>	<a href="https://opensea.io/collection/agents-brown-and-knows-by-mr-kaves" class="primary-button-link">
				<button class="primary-button">View Collection</button>
			</a>
		</div>
	</div>
	<!-- Repeat .project-card for more projects -->
</section>
<section class="featured-projects">

	<div class="project-card">
		
			<img src="{deciphericon}" alt="Doodle Labs" class="project-image" />
		
		
		<div class="project-description">
			<h3>DeCiphers
				by Irene Mamiye</h3>
			<p>
				
				Irene Mamiye's Ciphers series brought on chain through a generative lens.</p>
			<a href="https://opensea.io/collection/deciphers-by-irene-mamiye" class="primary-button-link">
				<button class="primary-button">View Collection</button>
			</a>
		</div>
	</div>
	<!-- Repeat .project-card for more projects -->
</section>
<section class="featured-projects">

	<div class="project-card">
		
			<img src="{imicon}" alt="Doodle Labs" class="project-image" />
		
		
		<div class="project-description">
			<h3>Industrial Melanism
				by Neil Grayson
				
				</h3>
			<p>Neil Grayson's renowned Industrial Melanism collection transformed for the blockchain.</p>
			<a href="https://opensea.io/collection/industrial-melanism-by-neil-grayson" class="primary-button-link">
				<button class="primary-button">View Collection</button>
			</a>
		</div>
	</div>
	<!-- Repeat .project-card for more projects -->
</section>
<section class="featured-projects">

	<div class="project-card">
		
			<img src="{vistaicon}" alt="Doodle Labs" class="project-image" />
		
		
		<div class="project-description">
			<h3>Vistas
				by Anton Ermakov
				
				</h3>
			<p>Imagining plausible, yet not-quite-real landscapes and cityscapes as geometric shapes that come together through layering and intersection.</p>
			<a href="https://opensea.io/collection/vistas-by-anton-ermakov " class="primary-button-link">
				<button class="primary-button">View Collection</button>
			</a>
		</div>
	</div>
	<!-- Repeat .project-card for more projects  https://opensea.io/collection/vistas-by-anton-ermakov -->
</section>
<footer class="site-footer">
		<div class="footer-logo">
			<img src="{doodlelabslogowhite}" alt="Doodle Labs" class="footer-logo-img" />
			<!-- Add any additional logo parts here -->
		</div>
		<div class="footer-icons">
			<a href="https://twitter.com/DoodleLabs" class="icon"><img src={twittericon} alt="Twitter"></a>
			<a href="https://discord.gg/DoodleLabs" class="icon"><img src={discordicon} alt="Discord"></a>
			<a href="mailto:info@doodlelabs.io" class="icon"><img src={emailicon} alt="Email"></a>
		</div>
	</footer>
	</main>
	
	
	<style>
		  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

		#background-video {
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		z-index: -1;
		overflow: hidden;
	}

	#background-video video {
		object-fit: cover;
		width: 100%;
		height: 100%;
	}
	
.main {
	max-width: 100%;
	margin: 0 auto;
	padding: 1em;
	background-color: hsla(0, 0%, 23%, 0.961);
	color: white;
}

	
		.intro {
			text-align: center;
		    padding: 0.3rem;
			color: white;
		}
	
		.welcome-image {
			max-width: 50%;
			height: auto;
			margin-bottom: 1em;
		}

		footer {
			padding: 1em;	
			color: white;
			text-align: center;
		}

		.logo {
			width: 125px;
			transition: filter 0.3s ease-in-out;
		}
		.logo:hover {
			filter: invert(1);
		}
		.site-header {
		width: 100%;
		position: fixed;
		top: 0;
		left: 0;
		background-color: #fff; /* You can set this to any color that matches your design */
		box-shadow: 0px 3px 10px rgba(0, 0, 0, 0.1); /* Shadow under the header */
		z-index: 1000;
	}

	.logo-container {
		display: flex;
		justify-content: flex-start; /* Aligns the logo to the right */
		padding: 1em;
	}

	.header-logo {
		width: 175px;
	}
	.main-logo {
		width: 180px;
	}
	.featured-projects {
	position: relative;
	width: "80vw";
	height: auto;
	
}
.primary-button-link {
	text-decoration: none; /* Removes underline from link */
	display: inline-block; /* Allows block-level styling */
}

.projects-title {
	font-family: 'Poppins';
	font-weight: 600;
	font-size: 24px;
	line-height: 36px;
	color: #000000;
}
.featured-projects {
	position: relative;
	max-width: 100%; /* Adjust as needed */
	margin: 0 auto; /* Centers the section */
	top: 20px; /* Adjust top spacing */
}

.project-card {
	position: relative;
	max-width: 100%; /* Allows the card to scale */
	height: 350px; /* Keep the height fixed */
	background: #FFFFFF;
	box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.25);
	border-radius: 8px;
	margin-bottom: 50px; /* Spacing between cards */
	display: flex;
	overflow: hidden; /* Hide overflow content */
}

.project-image {
	width: 66.05%; /* Adjust according to design */
	height: 100%;
	background-size: cover;
	border-radius: 8px;
}

.project-description {
	width: 33.95%; /* Adjust according to design */
	padding: 20px; /* Add padding for spacing */
	font-family: 'Poppins';
	font-weight: 600;
	font-size: 20px;
	line-height: 30px;
	color: #000000;
	display: flex;
	flex-direction: column;
	justify-content: space-between; /* Distributes space */
}

.primary-button {
	background: #5F36EC;
	border-radius: 8px;
	font-family: 'Poppins';
	font-weight: 700;
	font-size: 18px;
	line-height: 27px;
	text-align: center;
	color: #FFFFFF;
	padding: 10px 20px;
	cursor: pointer;
}
.hero {
	position: relative;
	max-width: 100%;
	margin: 0 auto;
	/*padding-top: 40px 0; /* Adjust for spacing */
	margin-top: 8vh;
	padding: 10px 0; /* Adjust for spacing */
	display: flex;
	align-items: center; /* Center vertically */
	justify-content: space-around; /* Distributes space */
}

.hero-text {
	width: 100%; /* You can adjust this */
	display: flex;
	align-items: center; /* Align logo and text vertically */
}

.hero-logo {
	width: 80; /* Adjust as needed */
/*	margin-right: 20px; Spacing between logo and text */
margin-left: 20px;
}

.hero-content {
	/* Add any additional styles if needed */
}

.hero-title {
	font-family: 'Poppins';
	font-weight: 600;
	font-size: 36px;
	line-height: 54px;
	color: #000000;
}

.hero-description {
	font-family: 'Poppins';
	font-weight: 300;
	font-size: 22px;
	line-height: 33px;
	color: #000000;
}

/* ... rest of the styles ... */

/* Add more specific path styles as needed */
.site-footer {
	position: relative;
	margin-top: 4vh;
	width: 100%;
	height: 100px;
	background: #5F36EC;
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 0 2%;
	box-sizing: border-box;
}

.footer-logo {
	display: flex;
	align-items: center;
}

.footer-logo-img {
	width: 130px;
}

.footer-icons {
	display: flex;
	align-items: center;
	gap: 20px;
}

.icon img {
	width: 28px; /* Adjust based on the size of your images */
	height: auto; /* Keeps the aspect ratio */
	display: block;
}


</style>