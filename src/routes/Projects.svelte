<!-- Projects.svelte -->

<script>
	import '../styles/projects.scss';
</script>

<section class="projects">
	<h3>
		<span class="icon-wrapper">
			<img src="/projects.png" alt="Icon" class="icon" />
		</span>
		<span class="text">Projects</span>
	</h3>

	<div class="project">
		<div class="left-column">
			<p class="date">2024</p>
		</div>
		<div class="right-column">
			<h4>
				<a
					href="https://findmovies-rho.vercel.app/"
					target="_blank"
					rel="noopener noreferrer"
					class="project-link"
				>
					<span class="iconLink">
						<img src="/lien.png" alt="Lien Icon" class="icon" />
					</span>
					FindMovies
				</a>
			</h4>
			<p class="description">
				Une application pour découvrir des films populaires avec filtres par genre et année et un
				système de pagination dynamique.
			</p>
			<p class="technos">React, Next.js, Chakra UI, TypeScript, TMDb API, Tailwind CSS</p>
		</div>
	</div>
	<div class="project">
		<div class="left-column">
			<p class="date">2024</p>
		</div>
		<div class="right-column">
			<h4>
				<a
					href="https://blog-vincent-achy.vercel.app/"
					target="_blank"
					rel="noopener noreferrer"
					class="project-link"
				>
					<span class="iconLink">
						<img src="/lien.png" alt="Lien Icon" class="icon" />
					</span>
					Blog.
				</a>
			</h4>
			<p class="description">
				Un blog construit avec Astro, Tailwind CSS, React et Tailwind Bootstrap Grid.
			</p>
			<p class="technos">Astro, Tailwind CSS, React et Tailwind Bootstrap Grid.</p>
		</div>
	</div>
	<div class="project">
		<div class="left-column">
			<p class="date">2023</p>
		</div>
		<div class="right-column">
			<h4>
				<a
					href="https://ams-architects.vercel.app/"
					target="_blank"
					rel="noopener noreferrer"
					class="project-link"
				>
					<span class="iconLink">
						<img src="/lien.png" alt="Lien Icon" class="icon" />
					</span>
					Ams-Architects
				</a>
			</h4>
			<p class="description">Un site présentant les divers travaux d'une agence d'architecture.</p>
			<p class="technos">Svelte, Vite, SCSS, TypeScript, Node.js, Express</p>
		</div>
	</div>
</section>
