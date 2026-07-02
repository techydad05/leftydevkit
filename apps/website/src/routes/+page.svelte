<svelte:head>
	<title>LeftyDevKit — Building tech for a better world</title>
	<meta name="description" content="Open-source progressive civic-tech tools. Free for candidates and organizers who align with our values." />
</svelte:head>

<!-- Hero -->
<section class="hero">
	<div class="container">
		<h1>Building tech<br>for a <span>better world</span></h1>
		<p>
			LeftyDevKit is an open-source toolkit and community of progressive tech builders.
			We build tools that help candidates, organizers, and communities fight for a more just future.
			The right has billions. We have <code>git push</code> and a dream.
		</p>
		<div class="hero-buttons">
			<a href="#projects" class="btn btn-primary">See the tools</a>
			<a href="#stream" class="btn btn-outline">Watch me build</a>
		</div>
	</div>
</section>

<!-- The Problem / Mission -->
<section id="mission">
	<div class="container">
		<div class="section-header">
			<h2>Why this exists</h2>
			<p>The right has billionaires funding their tech infrastructure. The left has us. I like our odds.</p>
		</div>
		<div class="mission">
			<p>
				Let's state the obvious: the right wing pours billionaire money into political tech —
				polished websites, data operations, targeted ad systems, media infrastructure that
				makes Fox News look like a garage project (it's actually worse — they have
				<a href="https://www.theguardian.com/us-news/2024/nov/07/peter-thiel-trump-victory-palantir" target="_blank">Peter Thiel's Palantir
				contractors</a> building their infrastructure).
			</p>
			<p>
				The left competes with passion, grassroots organizing, and people who believe in something
				bigger than themselves. That's not nothing — it's everything. But passion doesn't deploy a
				Docker container or A/B test a donation page.
			</p>
			<blockquote>
				We're building the tech infrastructure the left needs to meet the moment.
				Not by outspending — by outbuilding.
			</blockquote>
			<p>
				LeftyDevKit is the toolkit for that mission. Free campaign site templates for progressive
				candidates. Open-source scrapers that hold power accountable (<a href="https://www.propublica.org/" target="_blank">ProPublica</a>
				energy, community-powered). Data visualizations that make the truth impossible to ignore.
				A community of people who code for a cause instead of a cap table.
			</p>
			<p>
				The right has the money. We have <code>organize()</code>, <code>while (!free) {'{'}fight(){'}'}</code>,
				and each other.
			</p>
			<br/>
			<p><strong>If you're a progressive candidate, organizer, or activist — these tools are free.</strong>
			No strings. No gatekeeping. No "we'll need to run this by our sponsors." Just code that works
			for people who are trying to make the world less shitty.</p>
		</div>
	</div>
</section>

<!-- Projects -->
<section id="projects">
	<div class="container">
		<div class="section-header">
			<h2>Projects</h2>
			<p>What we're building right now</p>
		</div>
		<div class="project-grid">
			<div class="project-card">
				<div class="icon">🗳️</div>
				<h3>Campaign Site Template</h3>
				<p>A fast, modern, mobile-responsive website template for progressive candidates. Deploy in minutes, customize in hours. Free for anyone running for office — no questions asked.</p>
				<span class="status building">Building now</span>
			</div>
			<div class="project-card">
				<div class="icon">🔍</div>
				<h3>Scraping Hate</h3>
				<p>Distributed hate speech archival — evidence collection for accountability. Think the <a href="https://ddosecrets.com/" target="_blank">DDoSecrets</a> ethos applied to organized hate platforms. Community-powered, legally careful, publicly archived.</p>
				<span class="status" style="background: rgba(161, 161, 170, 0.1); color: var(--text-muted);">Research phase</span>
			</div>
			<div class="project-card">
				<div class="icon">📊</div>
				<h3>Geography of Power</h3>
				<p>Interactive data visualization of American political power — from <a href="https://ballotpedia.org/Supreme_Court_cases" target="_blank">Supreme Court decisions</a> to congressional voting patterns, dark money flows, and district-level demographics. See who actually runs shit.</p>
				<span class="status" style="background: rgba(161, 161, 170, 0.1); color: var(--text-muted);">In progress</span>
			</div>
			<div class="project-card">
				<div class="icon">📡</div>
				<h3>Corruption Counter</h3>
				<p>Real-time tracker documenting corruption cases and ethics violations by the Trump administration since January 2025. Data-sourced, fact-checked, updated live. Because someone has to keep score.</p>
				<span class="status building">Building now</span>
			</div>
			<div class="project-card">
				<div class="icon">🧰</div>
				<h3>Action Widgets</h3>
				<p>Embeddable tools for any progressive site: call-your-rep widgets, district data cards, protest proximity maps, and action alert systems. Drop-in HTML, zero configuration, works everywhere.</p>
				<span class="status" style="background: rgba(161, 161, 170, 0.1); color: var(--text-muted);">Planning</span>
			</div>
			<div class="project-card">
				<div class="icon">🤖</div>
				<h3>AI Cohost</h3>
				<p>An AI streaming cohost that listens, learns, and helps build on stream. Dialogue generation, TTS voice, overlay integration — the whole pipeline. Because building alone is boring.</p>
				<span class="status building">Building now</span>
			</div>
		</div>
	</div>
</section>

<!-- Stream -->
<section id="stream">
	<div class="container">
		<div class="section-header">
			<h2>Watch the build</h2>
			<p>Everything here is built in public, live on stream. Every line of code. Every bug. Every time I yell at my computer.</p>
		</div>
		<div class="stream-info">
			<div class="stream-embed">
				<p style="margin-bottom: 16px;">
					<span class="live-dot"></span> 
					Building live — coding, debugging, designing, shipping
				</p>
				<p style="color: var(--text-muted); margin-bottom: 12px; font-size: 0.9rem;">
					Schedule and streaming links coming soon.
				</p>
				<p style="color: var(--text-muted); margin-bottom: 20px; font-size: 0.85rem;">
					Watch a guy with ADHD and an axe to grind build the left's tech infrastructure in real time.
					Sometimes it works. Sometimes the GPU driver crashes. Either way, it's content.
				</p>
				<a href="https://github.com/techydad05/leftydevkit" class="btn btn-outline" target="_blank">Follow on GitHub</a>
			</div>
		</div>
	</div>
</section>

<!-- CTA -->
<section style="padding: 60px 0;">
	<div class="container" style="text-align: center;">
		<h2 style="font-size: 1.5rem; font-weight: 700; margin-bottom: 12px;">Need a tool for your campaign or org?</h2>
		<p style="color: var(--text-muted); max-width: 500px; margin: 0 auto 24px;">
			Progressive candidates and organizations get priority. I'll build it with you — on stream, for free.
			No contracts. No "let's circle back." Just code that works, built in public.
		</p>
		<a href="mailto:techydad05@users.noreply.github.com" class="btn btn-primary">Get in touch</a>
	</div>
</section>
