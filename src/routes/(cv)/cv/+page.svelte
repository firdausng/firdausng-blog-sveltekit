<script lang="ts">
	import { IconMail, IconBrandLinkedin, IconBrandGithub, IconArticle } from '@tabler/icons-svelte';

	let experiences = {
		companies: [
			{
				name: "Sitecore",
				positions: [
					{
						name: "Engineering Manager",
						duration: "January 2023 - Present",
						description: [
							"Leading a team of 3 developers and 3 QA professionals, I ensure successful project delivery and meet timelines"
						]
					},
					{
						name: "Senior Software Developer (Technical Lead)",
						duration: "October 2021 - December 2022",
						description: [
							"Help architect on architectural decision making, considering risk, security, scalability, feasibility and maintainability.",
							"Promote and teach best practices through automated testing, CI/CD and Agile methodologies.",
							"Developed component for the new sitecore product based on microservice and technologies such as .NET 6, azure, kafka, redis, cosmosdb, elasticsearch",
							"Launch Sitecore connect (Sitecore app that enable workflow automation that integrate with WOrkato)",
							"Inside the team that maintained existing Sitecore connector for Saleforce Integration",
						]
					}
				]
			},
			{
				name: "Cochlear",
				positions: [
					{
						name: "Software Engineer",
						duration: "May 2021 - September 2021",
						description: [
							"Developed sitecore jss site using javascript (react) and .NET"
						]
					}
				]
			},
			{
				name: "Sitecore",
				positions: [
					{
						name: "Developer",
						duration: "January 2020 - May 2021",
						description: [
							".NET developer and part of the Sitecore Salesforce Connector team to integrate Sitecore products with Salesforce"
						]
					},
					{
						name: "Senior Test Engineer in Security",
						duration: "January 2019 - December 2019",
						description: [
							"Handle Static Analysis Security Scan (SAST) report and work with dev team to improve their code from security perspective.",
							"Automate security report collection from all the team"
						]
					}
				]
			},
			{
				name: "Appspace",
				positions: [
					{
						name: "Automation Test Lead",
						duration: "August 2018 - December 2018",
						description: [
							"Lead the test automation effort and also ci/cd"
						]
					}
				]
			},
			{
				name: "IPG Mediabrands",
				positions: [
					{
						name: "Automation Test Lead",
						duration: "August 2018 - December 2018",
						description: [
							"Lead the test automation effort and also ci/cd"
						]
					}
				]
			},
			{
				name: "British Telecom Professional Services",
				positions: [
					{
						name: "Automation Engineer",
						duration: "May 2015 - August 2016",
						description: []
					}
				]
			},
			{
				name: "Maybank",
				positions: [
					{
						name: "Analyst",
						duration: "July 2013 - April 2015",
						description: []
					}
				]
			},
			{
				name: "HSBC",
				positions: [
					{
						name: "Analyst",
						duration: "July 2012 - June 2013",
						description: []
					}
				]
			},
		]
	}
</script>


<section class="flex flex-col gap-2 container mx-auto py-4">
		<nav class="flex flex-col gap-2 items-center justify-center">
			<h1 class="text-4xl">Firdaus Kamaruddin</h1>
			<div>
					<ul class="flex flex-wrap items-center justify-center gap-2">
						<li class="flex items-center justify-center gap-1">
							<IconMail />
							<p>firdauskamaruddin@hotmail.com</p>
						</li>
						<li class="flex items-center justify-center gap-1">
							<IconBrandLinkedin />
							<p>linkedin.com/in/firdaus-kamaruddin</p>
						</li>
						<li class="flex items-center justify-center gap-1">
							<IconBrandGithub />
							<p>github.com/firdausng</p>
						</li>
						<li class="flex items-center justify-center gap-1">
							<IconArticle />
							<p>firdausng.com</p>
						</li>
					</ul>
				<hr
					class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />
			</div>
		</nav>
		<div class="flex">
			<aside>

			</aside>
			<main class="flex flex-col">
					<section>
						<h2 class="text-2xl font-semibold">Summary</h2>
						<hr
							class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />
						<p>
							I specialize in DotNET (.NET), JavaScript, and TypeScript, with extensive experience developing microservices-based applications using Kafka, Redis, Cosmos DB, and Kubernetes. I excel in CI/CD and Test Automation and am proficient in performance and security testing. Leading a team of 3 developers and 3 QA professionals, I ensure successful project delivery and meet timelines. As a Software Architect aspirant, I am committed to staying up-to-date with the latest trends and tools, with a strong focus on automation and innovation.
						</p>
					</section>
				<section class="my-6">
					<h2 class="text-2xl font-semibold">Experience</h2>
					<hr
						class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />

					<div class=" flex flex-col gap-2">
						{#each experiences.companies as company (company)}
							<div class="py-2">
								<h3 class="text-xl font-semibold">{company.name}</h3>

								{#each company.positions as position (position)}
									<div class="py-2 pl-4">
										<div class="py-2">
											<h4 class="text-lg font-semibold ">{position.name}</h4>
											<p class="text-md font-semibold underline underline-offset-8">{position.duration}</p>
										</div>
										<div>
											<ul>
												{#each position.description as description (description)}
													<li>
														{description}
													</li>
												{/each}
											</ul>
										</div>
									</div>
								{/each}
							</div>
						{/each}
					</div>

				</section>

				<section class="my-4">
					<h2 class="text-2xl font-semibold">Skills</h2>
					<hr
						class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />

					<!--					mmu-->
					<div>
						<h3 class="text-xl py-2">Industry Knowledge</h3>
						<div>
							<p class="text-md font-semibold">TypeScript, playwright, Sitecore, Kubernetes, Containerization, Salesforce.com Development, Apache Kafka, Redis, Microservices, JMeter, LoadRunner, Performance Testing, Selenium WebDriver, Testing, Performance Tuning, Root Cause Analysis, ANSI C, Scripting, Test Execution, Test Planning</p>
						</div>

						<h3 class="text-xl py-2">Tools & Technologies</h3>
						<div>
							<p class="text-md font-semibold">
								Node.js, React.js, Azure Kubernetes Service (AKS), docker, ASP.NET MVC, REST APIs, .NET Framework, ASP.NET, Azure Cosmos DB, Elastic Stack (ELK), Elasticsearch, Microsoft Azure, Java, JavaScript, HP Quality Center, HTML, HP Diagnostics, C#							</p>
						</div>

						<h3 class="text-xl py-2">Languages</h3>
						<div>
							<p class="text-md font-semibold">
								English, Malay
						</div>
					</div>

				</section>

				<section class="my-4">
					<h2 class="text-2xl font-semibold">Education</h2>
					<hr
						class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />

					<!--					mmu-->
					<div>
						<h3 class="text-xl py-2">Bachelor of Engineering (BEng), Electrical and Electronics Engineering</h3>
						<div>
							<div class="flex justify-between py-2 ">
								<h4 class="text-lg font-semibold">Multimedia University</h4>
								<p class="text-md font-semibold">2012</p>
							</div>
						</div>
					</div>

				</section>


				<section class="my-4">
					<h2 class="text-2xl font-semibold">Certifications</h2>
					<hr
						class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />

					<!--					mmu-->
					<div>
						<h3 class="text-xl py-2">Microsoft Certified: Azure Developer Associate</h3>
						<div>
							<div class="flex justify-between py-2 ">
								<h4 class="text-lg font-semibold">Microsoft</h4>
								<p class="text-md font-semibold">2022</p>
							</div>
						</div>
					</div>

				</section>

			</main>
		</div>

</section>