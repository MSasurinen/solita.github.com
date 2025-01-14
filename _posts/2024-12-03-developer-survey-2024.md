---
layout: post
title: How We Feel about Tech, DevX and GenAI - Solita Developer Survey 2024 Results
author: jarnovayrynen
date: 2024-12-03 08:00:00 +0200
excerpt: >
  The Solita Developer Survey was conducted again in 2024. This time 322 Solitans from six countries shared their preferences regarding technologies, processes and tooling.  This summary of the survey results shows which tech is hot and which is not in Solita in 2024. 
tags:
  - Software development
  - Developer survey
  - DevOps
  - Testing
  - Open source
  - Competence development
  - Generative AI
  - Developer Experience
  - DevX
---

It is time to review the latest Solita Developer Survey results again! In this posting, we'll examine the tools, technologies and processes we use to do our daily work at Solita.

## Who Responded

This year we had 322 responses from six Solita countries. Most of the responses (201) came from Solita's origins Finland - Denmark was the second with 80 and Poland the third with 34 responses. Sweden (4), Estonia (2) and Belgium (1) had only a minor representation. The most common job role was still a Full-stack developer (172), followed by Backend developer (108) and Software architect (66). 38% of us said, they mostly work remotely from home. Interestingly, in Denmark all respondents work at the office whereas in Poland almost everyone works remotely. Finland has a mixture of these two.

## Competence Development
In the software industry, it's essential to keep one's skills relevant. Usually, everyday customer work offers many possibilities to develop oneself further. On top of that, 59% of the respondents say they spend at least some time on side projects or open-source contributions. That's quite a high number. On average, when asked how well can you develop your competencies in your working time, the result was 4.52 points out of 7 which can be considered quite good. As the most popular learning platform, YouTube is still number one, followed by O'Reilly and Udemy. Of the developer conferences, our developers have followed Apply WWDC, Google I/O, AWS re:Invent and Disobey, to name but a few. On top of external conferences, [Solita has its own DevDay](https://dev.solita.fi/2021/12/13/devday-of-solita.html) where we spend every year a whole day with internal conference talks on multiple tracks, and have dinner and fun in the evening.

## OS, IDE and Tooling
When it comes to building something, you need proper tools. The ones you know, the ones you trust, or the ones you would like to learn. As the leading operating system, Windows had a 48% share, followed by Mac 43% and Linux 9%. The most popular Linux distribution was Ubuntu, as usual. The most used IDE/editor was Visual Studio Code with 61%, followed by IntelliJ IDEA with 45%. A developer can use more than one IDE, depending on the work context. Some of our hard-core developers have always had tough discussions between Vim vs. Emacs - this time, Vim beat this race with 28 vs. 11 users.

[![Code editor or IDE of choice at Solita in 2024](/img/developer-survey-2024/DEV_survey_2024-ide.png)](/img/developer-survey-2024/DEV_survey_2024-ide.png)

## Programming Languages and Software Stacks
For many, the most important thing in software development is the programming language. Some feel they are all just tools, while others are passionate and would not like to switch their favorite language at any cost. In 2024, our most popular language to work with was C# with 28%, followed by TypeScript at 15%, Kotlin at 11%, Java at 10%, Clojure at 7% and Python at 6%. There is a difference with the most liked and most used programming language too: the reality is that the most used one was SQL with 63% (almost all applications have a database) - also frontend behemoths with TypeScript at 61% and JavaScript at 60% were among top three most used ones. Interestingly, 2024 is the first time TypeScript has surpassed plain JavaScript - we expect this trend to continue. Also, C#, Go and Swift saw rising adoption.

When it comes to databases, PostgreSQL keeps the lead with a good margin. We also see cloud-based managed databases gain popularity, such as Azure SQL and Amazon Aurora. Oracle, MongoDB and MariaDB were in decline.

[![Most liked programming languages at Solita in 2024](/img/developer-survey-2024/DEV_survey_2024-most_liked_languages.png)](/img/developer-survey-2024/DEV_survey_2024-most_liked_languages.png)
[![Most used programming languages at Solita in 2024](/img/developer-survey-2024/DEV_survey_2024-most_used_languages.png)](/img/developer-survey-2024/DEV_survey_2024-most_used_languages.png)

## CI/CD Pipelines, Deployments and DevOps
To ensure stress-free (and almost bug-free) releases, you need proper continuous integration and deployment pipelines. Here we see a major, yet not unexpected, shift: Jenkins has given way to cloud-based solutions from the pole position to number four. Azure DevOps and GitHub Actions have taken the undisputed lead, followed by Gitlab CI. This is reflected in the wider adoption of cloud-based environments generally. When many of our customers shift their operations from on-prem to the cloud, it also impacts the tooling used for CI, packaging and deployment.

## Testing, Monitoring and Security
While public cloud solutions gain popularity, also the willingness to invest in testing, monitoring and security increases. This can be seen in the results of our survey as well. In test automation maturity, the biggest winner is automated security tests almost doubling its adoption to 13% of respondents. On the monitoring side, almost all items saw a small rise, such as client-side error logging, performance monitoring, automated alerts and audit logs. In general, this probably stems from customers' higher awareness of possible risks if logging, monitoring or security are neglected.

## Generative AI - Adoption Rate and Usage
Generative AI, or GenAI, continues to be a hot topic in our industry. Solita has made a conscious effort to increase the competencies in this area; both in the tooling and [the capabilities we use to help our customers](https://www.solita.fi/generative-ai-in-software-development/). We all must become more aware and learn about these capabilities as they develop at a fast rate. Current production-level solutions rely very much on human-in-the-loop, but more agentic and autonomous applications are being explored by various industries. 38% of the respondents use GenAI daily and 26% weekly, so you can say most of us do use GenAI in our daily work. The methods vary, depending on the needs, personal know-how and even customer policies. We have internal discussion channels and info sessions on various GenAI methods and possibilities to play around with them in sandbox environments. The most popular GenAI services were GenAI chats (90%), GitHub CoPilot 59% and image creators such as Dall-E (27%). But many people go beyond these: things like OpenAI API, LLMs and neural networks, and M365 Copilot are reported to be used by many. GenAI is used for example to help decision-making, code autocompletion, aid in creating test code, explain errors and automate routine tasks.

[![Most popular GenAI tools at Solita in 2024](/img/developer-survey-2024/DEV_survey_2024-genai_tools.png)](/img/developer-survey-2024/DEV_survey_2024-genai_tools.png)

## Developer Experience (What Do We Value)
For the first time, our survey also had a section called Developer Experience, or DevX. There we wanted to know, what kind of things our experts value the most, in terms of customership, development environment, used practices and needed support. Some of the most important things for us in this perspective were:
- I can act according to my values in my work
- I can set up my development environment easily
- I can influence the improvement of development practices
- I feel comfortable asking my teammates for help
- Support from the project lead (e.g. priorities and decision-making)

[![What developers value in Developer Experience at Solita in 2024](/img/developer-survey-2024/DEV_survey_2024-developer_experience.png)](/img/developer-survey-2024/DEV_survey_2024-developer_experience.png)

## Career Opportunities at Solita
We seek constantly more people who enjoy solving customer problems with tech and are eager to develop their skills
further. You'll find our open jobs at [www.solita.fi/en/careers/](https://www.solita.fi/en/careers/).

## Previous Solita Developer Surveys

The tech landscape evolves quite fast. To better understand how time has shaped our preferences, we recommend you read
also the previous survey postings.

* [**Solita Developer Survey 2022**](https://dev.solita.fi/2022/12/15/developer-survey-2022.html)
* [**Solita Developer Survey 2020**](https://dev.solita.fi/2020/12/10/developer-survey-2020.html)
* [**Solita Developer Survey 2016**](https://dev.solita.fi/java/2016/05/13/Developers-love-spaces.html)