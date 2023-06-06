<script>
	import githubIcon from 'feather-icons/dist/icons/github.svg';
	import linkedinIcon from 'feather-icons/dist/icons/linkedin.svg';
	import twitterIcon from 'feather-icons/dist/icons/twitter.svg';
	import mailIcon from 'feather-icons/dist/icons/mail.svg';

	import Card from '../Card.svelte';
	import CardGrid from '../CardGrid.svelte';
	import Section from '../Section.svelte';

	let textHighlight = 'text-blue-600 font-bold';
</script>
<Section title="About">
	<CardGrid>
		<Card color="bg-orange-200" size={6}>
			<div class="">
				<p class="mb-3">
					<p class="mb-3">
						Hey, I am Logan. I am passionate about web development and how it can make our lives
						<span class={textHighlight}>easier and more enjoyable</span>.
					</p>
				<p class="mb-3">
					I am a Student at {' '}
					<span class={textHighlight}>Edina High School</span> in Minnesota, United States. I spent a lot of time
					testing, developing, and creating applications and websites. I also spent time innovating and 
					educating myself on new technologies and software.
				<p class="mb-3">
					I developed this website to <span class={textHighlight}>showcase</span> my projects and creations. 
					Although most of my projects are closed-source, I like to publish my open-sourced ones to the public. 
					When I get the time, I will post my large projects to this portfolio. For now, I need to study. 💪🔥
				</p>
				<p class="mb-3">
					There will be far more to come in the {' '}
					<a href="https://silt.one" class="underline" target="_blank" rel="noreferrer">
						future,
					</a>
					as I am just getting started. With that said, keep your eyes peeled, and I'll see you <span class={textHighlight}>shortly</span>...
				</p>
			</div>
		</Card>

		<Card color="bg-orange-300" size={2}>
			<div class="flex gap-12 flex-col items-center justify-center h-full">
				<h2 class="font-bold text-lg ">Connect with me</h2>
				<a href="https://github.com/lbracken812/">
					<img src={githubIcon} alt="Github" class="w-8 h-8" />
				</a>
				<a href="https://www.linkedin.com/in/korral/">
					<img src={linkedinIcon} alt="Linkedin" class="w-8 h-8" />
				</a>
				<a href="mailto:logan@korral.me">
					<img src={mailIcon} alt="mail" class="w-8 h-8" />
				</a>
			</div>
		</Card>
	</CardGrid>
</Section>

