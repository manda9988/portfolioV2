<!-- Contact.svelte -->

<script>
	import '../styles/contact.scss';
</script>

<section class="contact">
	<h3>
		<span class="icon-wrapper">
			<img src="/contacts.png" alt="Icon" class="icon" />
		</span>
		<span class="text">Contact</span>
	</h3>

	<div class="contact-items">
		<div class="contact-item">
			<p class="email">vincent.achy@gmail.com</p>
		</div>

		<div class="contact-item">
			<a href="https://github.com/manda9988" target="_blank" rel="noopener noreferrer">
				<span class="iconLink">
					<img src="/lien.png" alt="Lien Icon" class="icon" />
				</span>
				Github
			</a>
		</div>

		<div class="contact-item">
			<a
				href="https://www.linkedin.com/in/vincent-achy-1704421a9/"
				target="_blank"
				rel="noopener noreferrer"
			>
				<span class="iconLink">
					<img src="/lien.png" alt="Lien Icon" class="icon" />
				</span>
				LinkedIn
			</a>
		</div>

		<div class="contact-item">
			<a href="/cv_frontend_vincent_achy.pdf" target="_blank" rel="noopener noreferrer">
				<span class="iconLink">
					<img src="/lien.png" alt="Lien Icon" class="icon" />
				</span>
				Curriculum vitæ
			</a>
		</div>
	</div>
</section>
