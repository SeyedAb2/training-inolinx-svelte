<script>
	import {onMount} from "svelte";
	import Header from "./Header.svelte";
	import ArtistList from "./ArtistList.svelte";
	import Team from "./Team.svelte";
	import Footer from "./Footer.svelte";
	let searchTerm = "Dr. Masoud Aghaeei";
	let Pic = "image/1.jpeg";
	let Time = "21:24 15 Jun 2021";
	let introText = "Hi I'm very happy now for visiting my website by your dear visiter you can make me happy by sign-up and use donnate in this web site for help us to countinue our job powerful";
	let artists = [];

	onMount(
		async() => {
			const res = await fetch(`data.JSON`);
			artists = await res.json();
		}
	)
</script>

<style global lang="scss">
	@import "../node_modules/bootstrap/scss/bootstrap.scss";
	$color :red;
	body{
		padding: 0;
		margin: 0;
		background-repeat: no-repeat;
		background: rgb(192,201,218);
		background: linear-gradient(90deg, rgba(192,201,218,1) 0%, rgba(238,240,208,1) 50%, rgba(192,201,218,1) 100%);
	}
	a , a:hover{
		text-decoration: none;
		h2{
		color: $color;
		}
	}
	
</style>
<Header />
<div class="container">
	<ArtistList {searchTerm} {Pic} {introText} {Time}/>	
	<Team {artists}/>
</div>
<br><br><br>
<Footer />