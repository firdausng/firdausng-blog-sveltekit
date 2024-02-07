<script lang="ts">
	import { IconMail, IconBrandLinkedin, IconBrandGithub, IconArticle } from '@tabler/icons-svelte';

	let experiences = {
		companies: [
			{
				name: 'Sitecore',
				positions: [
					{
						name: 'Engineering Manager',
						duration: 'January 2023 - Present',
						description: [
							'Leading a team of 3 developers and 3 QA professionals, I ensure successful project delivery and meet timelines'
						],
						achievements: [
							{
								name: "Sitecore Connect",
								details: [
									"Sitecore Connect, is a Low-code / No-code integration platform built on Workato. This platform enables your organization to connect Sitecore products with the rest of your tech stack with ease.",
									"Involve in the team that develop and deploy sitecore connect from scratch",
									"https://developers.sitecore.com/integrations/connect"
								]
							},
							{
								name: "Sitecore Mesh",
								details: [
									"Sitecore Mesh is an internal application to support integration between any Sitecore product",
									"It is an event-driven architecture that can handle million of event come in and also publish those event to a webhook or any other system",
									"Involve in the team that develop and deploy sitecore mesh from scratch",
								]
							},
							{
								name: "Sitecore Audit",
								details: [
									"Sitecore Audit is an Sitecore application that provide audit data to any Sitecore product",
									"Involve in the team that develop and deploy sitecore audit from scratch",
								]
							}
						]
					},
					{
						name: 'Senior Software Developer (Technical Lead)',
						duration: 'October 2021 - December 2022',
						description: [
							'Help architect on architectural decision making, considering risk, security, scalability, feasibility and maintainability.',
							'Promote and teach best practices through automated testing, CI/CD and Agile methodologies.',
							'Developed component for the new sitecore product based on microservice and technologies such as .NET 6, azure, kafka, redis, cosmosdb, elasticsearch',
							'Launch Sitecore connect (Sitecore app that enable workflow automation that integrate with WOrkato)',
							'Inside the team that maintained existing Sitecore connector for Saleforce Integration'
						],
						achievements: [
							{
								name: "Sitecore Connect",
								details: [
									"Sitecore Connect, is a Low-code / No-code integration platform built on Workato. This platform enables your organization to connect Sitecore products with the rest of your tech stack with ease.",
									"Involve in the team that develop and deploy sitecore connect from scratch",
									"https://developers.sitecore.com/integrations/connect"
								]
							},
							{
								name: "Sitecore Mesh",
								details: [
									"Sitecore Mesh is an internal application to support integration between any Sitecore product",
									"It is an event-driven architecture that can handle million of event come in and also publish those event to a webhook or any other system",
									"Involve in the team that develop and deploy sitecore mesh from scratch",
								]
							}
						]
					}
				]
			},
			{
				name: 'Cochlear',
				positions: [
					{
						name: 'Software Engineer',
						duration: 'May 2021 - September 2021',
						description: [
							'Developed sitecore jss site using javascript (react) and .NET'
						]
					}
				]
			},
			{
				name: 'Sitecore',
				positions: [
					{
						name: 'Developer',
						duration: 'January 2020 - May 2021',
						description: [
							'.NET developer and part of the Sitecore Salesforce Connector team to integrate Sitecore products with Salesforce'
						],
						achievements: [
							{
								name: "Sitecore Connector",
								details: [
									"Responsible on the launch of Sitecore connector integration with Salesforce that enable event from Salesforce to be sent to Sitecore",
									"Involve in the team that develop connector",
									"https://www.sitecore.com/products/connectors"
								]
							}
						]
					},
					{
						name: 'Senior Test Engineer in Security',
						duration: 'January 2019 - December 2019',
						description: [
							'Handle Static Analysis Security Scan (SAST) report and work with dev team to improve their code from security perspective.',
							'Automate security report collection from all the team'
						]
					}
				]
			},
			{
				name: 'Appspace',
				positions: [
					{
						name: 'Automation Test Lead',
						duration: 'August 2018 - December 2018',
						description: [
							'Lead the test automation effort and also ci/cd'
						],
						achievements: [
							{
								name: "Test Automation Framework",
								details: [
									"Responsible on building the Test automation from scratch",
									"Mentor other QA engineer on how to automate as well provide any solution for their need such as Test report and test case automation",
								]
							}
						]
					}
				]
			},
			{
				name: 'IPG Mediabrands',
				positions: [
					{
						name: 'Automation Test Lead',
						duration: 'August 2018 - December 2018',
						description: [
							'Lead the test automation effort and also ci/cd'
						],
						achievements: [
							{
								name: "Test Automation Framework",
								details: [
									"Responsible on building the Test automation from scratch",
									"Mentor other QA engineer on how to automate as well provide any solution for their need such as Test report and test case automation",
								]
							}
						]
					}
				]
			},
			{
				name: 'British Telecom Professional Services',
				positions: [
					{
						name: 'Automation Engineer',
						duration: 'May 2015 - August 2016',
						description: [],
						achievements: [
							{
								name: "Test Automation Framework",
								details: [
									"Responsible on building the Test automation from scratch",
									"Mentor other QA engineer on how to automate as well provide any solution for their need such as Test report and test case automation",
								]
							}
						]
					}
				]
			},
			{
				name: 'Maybank',
				positions: [
					{
						name: 'Analyst',
						duration: 'July 2013 - April 2015',
						description: []
					}
				]
			},
			{
				name: 'HSBC',
				positions: [
					{
						name: 'Analyst',
						duration: 'July 2012 - June 2013',
						description: []
					}
				]
			}
		]
	};

	let summary = {
		text: [
			'I specialize in DotNET (.NET), JavaScript, and TypeScript, with extensive experience developing microservices-based applications using Kafka, Redis, Cosmos DB, and Kubernetes.',
			'I familiar with agile methodology of software development',
			'I excel in CI/CD and Test Automation and am proficient in performance and security testing. ',
			'Leading a team of 3 developers and 3 QA professionals, I ensure successful project delivery and meet timelines. ',
			'As a Software Architect aspirant, I am committed to staying up-to-date with the latest trends and tools, with a strong focus on automation and innovation.'
		]
	};

	let skills = {
		industryKnowledge: [
			"C#",
			"Microsoft Azure",
			"JavaScript",
			"TypeScript",
			"Node.js",
			"React.js",
			"Azure Kubernetes Service (AKS)",
			"docker",
			"ASP.NET MVC",
			"REST APIs",
			".NET Framework",
			"ASP.NET",
			"Azure Cosmos DB",
			"Elasticsearch",
			"Kubernetes",
			"Containerization",
			"Apache Kafka",
			"Redis",
			"Microservices",
			"playwright",
			"Sitecore",
			"Salesforce.com Development",
			"JMeter",
			"LoadRunner",
			"Performance Testing",
			"Selenium WebDriver",
			"Testing",
			"Performance Tuning",
			"Root Cause Analysis",
			"Scripting",
			"Test Execution",
			"Test Planning"
		],
		language: [
			"English", "Malay"
		]
	}

	let contactDetail = [
		{
			name: 'phone',
			value: '010-2345257'
		},
		{
			name: 'email',
			value: 'firdauskamaruddin@hotmail.com'
		}
	]
</script>


<section class="flex flex-col gap-2 container mx-auto py-4 p-2">
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
	<div class="flex gap-4">
		<aside class="w-1/5 flex flex-col gap-2 break-words">
				<section>
					<h3 class="text-2xl font-semibold">Details</h3>
					<hr
						class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />
					{#each contactDetail as detail}
						<div class="p-2">
							<p class="capitalize font-semibold">{detail.name}</p>
							<p class="">{detail.value}</p>
						</div>
					{/each}
				</section>

			<section>
				<h3 class="text-2xl font-semibold">Skills</h3>
				<hr
					class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />
				{#each skills.industryKnowledge as skill}
					<p class="pb-2 pr-4 text-sm">{skill}</p>
				{/each}
			</section>

			<section>
				<h3 class="text-2xl font-semibold">Languages</h3>
				<hr
					class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />
				{#each skills.language as language}
					<p class="pb-2 pr-4 text-sm">{language}</p>
				{/each}
			</section>
		</aside>
		<main class="flex flex-col">
			<section>
				<h2 class="text-2xl font-semibold">Profile</h2>
				<hr
					class="my-4 h-0.5 border-t-0 bg-neutral-400 opacity-100 dark:opacity-50" />

				{#each summary.text as text}
					<p>{text}</p>
				{/each}

			</section>

			<section class="my-6">
				<h2 class="text-2xl font-semibold">Employment History</h2>
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
										<ul class="list-disc">
											{#each position.description as description (description)}
												<li>
													{description}
												</li>
											{/each}
										</ul>
									</div>

									{#if position.achievements}
										<div class="pt-2">
											<h4 class="text-md font-semibold ">Achievements</h4>
										</div>
										{#each position.achievements as achievement (achievement)}
											<div class="pl-4">
												<div class="py-2">
													<p class="text-md font-semibold underline underline-offset-8">{achievement.name}</p>
												</div>
												<ul class="list-disc">
													{#each achievement.details as detail (detail)}
														<li>
															{detail}
														</li>
													{/each}

												</ul>
											</div>
										{/each}
									{/if}

								</div>
							{/each}
						</div>
					{/each}
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

		</main>
	</div>

</section>

