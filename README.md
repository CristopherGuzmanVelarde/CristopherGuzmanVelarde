<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>GitHub Profile</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
	<style>
		* {
			margin: 0;
			padding: 0;
			box-sizing: border-box;
			font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
		}

		body {
			background: #0d1117;
			color: #c9d1d9;
			line-height: 1.6;
		}

		.container {
			max-width: 1200px;
			margin: 0 auto;
			padding: 2rem;
		}

		.profile-header {
			text-align: center;
			margin-bottom: 2rem;
			animation: fadeIn 1s ease-in;
		}

		.profile-img {
			width: 200px;
			height: 200px;
			border-radius: 50%;
			border: 4px solid #238636;
			margin-bottom: 1rem;
			transition: transform 0.3s ease;
		}

		.profile-img:hover {
			transform: scale(1.05);
		}

		.name {
			font-size: 2.5rem;
			color: #58a6ff;
			margin-bottom: 0.5rem;
		}

		.bio {
			color: #8b949e;
			margin-bottom: 1.5rem;
		}

		.stats {
			display: flex;
			justify-content: center;
			gap: 2rem;
			margin-bottom: 2rem;
		}

		.stat-item {
			background: #161b22;
			padding: 1rem;
			border-radius: 10px;
			text-align: center;
			transition: transform 0.3s ease;
		}

		.stat-item:hover {
			transform: translateY(-5px);
		}

		.social-links {
			display: flex;
			justify-content: center;
			gap: 1.5rem;
			margin-bottom: 2rem;
		}

		.social-icon {
			font-size: 1.5rem;
			color: #8b949e;
			transition: color 0.3s ease;
		}

		.social-icon:hover {
			color: #58a6ff;
		}

		.projects {
			display: grid;
			grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
			gap: 1.5rem;
		}

		.project-card {
			background: #161b22;
			border-radius: 10px;
			padding: 1.5rem;
			transition: transform 0.3s ease;
		}

		.project-card:hover {
			transform: translateY(-5px);
		}

		@keyframes fadeIn {
			from {
				opacity: 0;
				transform: translateY(20px);
			}
			to {
				opacity: 1;
				transform: translateY(0);
			}
		}
	</style>
</head>
<body>
	<div class="container">
		<div class="profile-header">
			<img src="https://github.com/[your-username].png" alt="Profile Picture" class="profile-img">
			<h1 class="name">Your Name</h1>
			<p class="bio">Full Stack Developer | Open Source Enthusiast</p>
			
			<div class="stats">
				<div class="stat-item">
					<h3>Repositories</h3>
					<p>20+</p>
				</div>
				<div class="stat-item">
					<h3>Followers</h3>
					<p>100+</p>
				</div>
				<div class="stat-item">
					<h3>Following</h3>
					<p>50+</p>
				</div>
			</div>

			<div class="social-links">
				<a href="https://github.com/[your-username]" class="social-icon">
					<i class="fab fa-github"></i>
				</a>
				<a href="https://linkedin.com/in/[your-username]" class="social-icon">
					<i class="fab fa-linkedin"></i>
				</a>
				<a href="https://twitter.com/[your-username]" class="social-icon">
					<i class="fab fa-twitter"></i>
				</a>
				<a href="mailto:your.email@example.com" class="social-icon">
					<i class="fas fa-envelope"></i>
				</a>
			</div>
		</div>

		<div class="projects">
			<div class="project-card">
				<h3>Project 1</h3>
				<p>Description of your awesome project goes here.</p>
			</div>
			<div class="project-card">
				<h3>Project 2</h3>
				<p>Description of your awesome project goes here.</p>
			</div>
			<div class="project-card">
				<h3>Project 3</h3>
				<p>Description of your awesome project goes here.</p>
			</div>
		</div>
	</div>
</body>
</html>
