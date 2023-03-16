<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Salong Clase</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}
		
		header {
			background-image: url("salong-clase-header.jpg");
			background-size: cover;
			height: 100vh;
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			color: #fff;
		}
		
		h1 {
			font-size: 5rem;
			margin: 0;
		}
		
		nav {
			background-color: #fff;
			box-shadow: 0 4px 6px rgba(0,0,0,.1);
			position: sticky;
			top: 0;
			z-index: 1;
		}
		
		nav ul {
			margin: 0;
			padding: 0;
			list-style: none;
			display: flex;
			justify-content: center;
		}
		
		nav li {
			margin: 0 1rem;
		}
		
		nav a {
			color: #333;
			text-decoration: none;
			font-weight: bold;
			text-transform: uppercase;
			transition: color .2s ease-in-out;
		}
		
		nav a:hover {
			color: #ff5a5f;
		}
		
		.services {
			padding: 5rem;
			display: flex;
			flex-wrap: wrap;
			justify-content: space-between;
			align-items: center;
			background-color: #f7f7f7;
		}
		
		.service {
			flex-basis: calc(33.33% - 1rem);
			margin-bottom: 2rem;
			background-color: #fff;
			box-shadow: 0 4px 6px rgba(0,0,0,.1);
			padding: 2rem;
			display: flex;
			flex-direction: column;
			align-items: center;
			text-align: center;
		}
		
		.service img {
			max-width: 100%;
			margin-bottom: 1rem;
		}
		
		.service h2 {
			font-size: 2rem;
			margin: 0;
			margin-bottom: 1rem;
		}
		
		.service p {
			font-size: 1.2rem;
			margin: 0;
			margin-bottom: 1rem;
			line-height: 1.5;
		}
		
		@media only screen and (max-width: 768px) {
			.service {
				flex-basis: calc(50% - 1rem);
			}
		}
		
		@media only screen and (max-width: 576px) {
			header {
				height: auto;
				padding-top: 5rem;
				padding-bottom: 5rem;
			}
			
			h1 {
				font-size: 3rem;
			}
			
			.services {
				padding: 2rem;
			}
			
			.service {
				flex-basis: 100%;
