# patrickoswald319.github.io

<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<link
			href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"
			rel="stylesheet"
			integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi"
			crossorigin="anonymous"
		/>
		<link
			rel="stylesheet"
			href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0"
		/>
		<link rel="preconnect" href="https://fonts.googleapis.com" />
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
		<link
			href="https://fonts.googleapis.com/css2?family=Cabin&display=swap"
			rel="stylesheet"
		/>
		<link rel="stylesheet" href="style.css" />
		<title>Maxflix</title>
	</head>
	<body>
		<div class="container-fluid">
			<nav class="row">
				<div class="col-1">
					<img src="img/logo.png" class="img-fluid" />
				</div>
				<div class="col-8" id="linksBar">
					<span>Home</span>
					<span>TV Shows</span>
					<span>Movies</span>
					<span>New & Popular</span>
				</div>
				<div class="col-3 text-end" id="icons">
					<span class="material-symbols-outlined"> search </span>
					<span class="material-symbols-outlined">
						notifications
					</span>
					<span class="material-symbols-outlined"> account_box </span>
				</div>
			</nav>
			<!-- end of nav-->
			<section class="row" id="headlineContent">
				<div class="col-5">
					<div id="seriesRow">
						<img id="netflixN" src="img/netflix-N.png" />
						Series
					</div>
					<!-- end of Series row-->
					<div id="showName">SNOW</div>
					<div id="trendingStatus">
						<img src="img/netflix-top10-icon.png" />
						<span>#2 in TV Shows Today</span>
					</div>
					<p>
						The eight close-knit siblings of the Bridgerton family
						Ibok for love and happiness in London high society.
						Inspired by Julia Quinn's bestselling novels.
					</p>
					<div id="buttonRow">
						<button
							id="play"
							class="d-inline-flex align-items-center"
						>
							<span class="material-symbols-outlined">
								play_arrow
							</span>
							<span>Play</span>
						</button>
						<button
							id="moreInfo"
							class="d-inline-flex align-items-center"
						>
							<span class="material-symbols-outlined">
								info
							</span>
							<span>More Info</span>
						</button>
					</div>
				</div>
				<!-- end of col-5 with show details-->
				<div class="col-5">
					<!--spacer push the rating column to the right spot-->
				</div>
				<div
					class="col-2 d-inline-flex align-items-center justify-content-end"
					id="ratingCol"
				>
					<span class="material-symbols-outlined"> refresh </span>
					<span id="rating">TV-MA</span>
				</div>
			</section>
			<section id="firstVideoRowLabel">
				<h5>Released in the Past Year</h5>
				<div class="row">
					<div class="col-2">
						<img src="img/show1.jpg" class="img-fluid" />
					</div>
					<div class="col-2">
						<img src="img/show2.jpg" class="img-fluid" />
					</div>
					<div class="col-2">
						<img src="img/show3.jpg" class="img-fluid" />
					</div>
					<div class="col-2">
						<img src="img/show4.jpg" class="img-fluid" />
					</div>
					<div class="col-2">
						<img src="img/show5.jpg" class="img-fluid" />
					</div>
					<div class="col-2">
						<img src="img/show6.webp" class="img-fluid" />
						<p>apple
					</div>
				</div>
			</section>
		</div>
		<!-- end of container-->
		<div id="abnormalScreenSize">
			<h1>Woah! Your screen is either really big, or really small.</h1>
			<p>This site was designed for goldilocks sized screens.</p>
		</div>
	</body>
</html>
