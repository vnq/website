<template>
	<footer>
		<div class="inner-max">
			<div class="footer-container">
				<div class="footer-col">
					<logo />
					<p class="small-text">
						Copyright © {{ new Date().getFullYear() }} CodeCarrot. All rights reserved.
					</p>
				</div>

				<div class="footer-col">
					<nav class="footer-nav">
						<g-link class="footer-link" to="/partners"> Partners </g-link>
						<g-link class="footer-link" to="/docs"> Docs </g-link>
					</nav>
				</div>

				<div class="footer-col">
					<div class="footer-social">
						<a
							href="https://github.com/logchimp/logchimp"
							class="footer-col-item"
							target="_blank"
						>
							<github-icon />
						</a>
						<a
							href="https://www.patreon.com/mittalyashu"
							class="footer-col-item"
							target="_blank"
						>
							<patreon-icon />
						</a>
						<a
							href="https://opencollective.com/logchimp"
							class="footer-col-item"
							target="_blank"
						>
							<opencollective-icon />
						</a>
						<a
							href="https://discord.gg/A7mztcC"
							class="footer-col-item"
							target="_blank"
						>
							<discord-icon />
						</a>
						<a
							href="https://twitter.com/logchimp"
							class="footer-col-item"
							target="_blank"
						>
							<twitter-icon />
						</a>
					</div>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>
// components
import Logo from "../../components/Logo";

// icons
import GithubIcon from "../../components/icons/github";
import DiscordIcon from "../../components/icons/Discord";
import PatreonIcon from "../../components/icons/Patreon";
import TwitterIcon from "../../components/icons/Twitter";
import OpencollectiveIcon from "../../components/icons/Opencollective";

export default {
	name: "SmallFooter",
	components: {
		Logo,

		// icons
		GithubIcon,
		DiscordIcon,
		PatreonIcon,
		TwitterIcon,
		OpencollectiveIcon
	}
};
</script>
