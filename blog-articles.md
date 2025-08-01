# Hello World - May 25, 2025 - Chris Brown

Welcome to our blog! This is the first post, more will be coming soon 👀...

About Us: We are the Code World, No Blanket lab---a software engineering research group in the Department of Computer Science at [Virginia Tech](https://cs.vt.edu) 🦃. Our research uses empirical, interdisciplinary, and automated methods to improve the behavior, productivity, decision-making of software engineers---we study software development and software developers.

More details about us and our research are available [here](https://code-world-no-blanket.github.io). This group is led by [Dr. Chris Brown](https://chbrown13.github.io).

---

# We Hosted a Workshop for Practitioners---No One Came - Jun 5, 2025 - Chris Brown

As part of a [recent grant](https://chbrown13.github.io/files/grants/Brown_CCI_2025.pdf), we were required to host a topical workshop to share ideas and promote collaboration among stakeholders. I decided to design our workshop primarily for software practitioners (individuals who apply software engineering concepts in real-world industry settings). As one of our [research group goals](about.html) is to explore how we might bridge the gap between academia and industry---this seemed like the perfect opportunity.

## The Workshop

The workshop was organized to be an interactive "working group" on topics related to our grant [testing and securing user interfaces in CI/CD pipelines](https://code-world-no-blanket.github.io/cci-workshop.html). The event featured research presentations share and collect feedback on preliminary research findings, interactive discussions to uncover challenges in practice, and brainstorming sessions to motivate new solutions and researh directions. We espectially hoped to target practitioners for our workshop to gain industry perspectives and inspire future work with practical implications and relevance.

We started planning the workshop activities in late March (~7 weeks before the event) and finalized the details to share in mid-April (~3.5 weeks before). 20 people registered to attend through our online form (14 in-person and 6 virtual, mostly from VT but some external). We booked a conference room on campus and two graduate students put in a lot of work to prepare presentation slides and activities related to their research from this project.

Yet, when the time for the workshop arrived---no one showed up*. Actually two people came---another graduate student from our research group and a CS faculty member working on related research---and I am extremely grateful for their attendance. However, this was way less than the expected attendance and not a single software practitioner (the intended audience) joined our workshop.

We still had a great time---and received valuable insights and feedback on our work. However, I was very dissapointed we were unable to attract a broader audience. Here is an overview of what we tried to attract practitioners to our workshop, and a brief reflection on what to do differently next time.

## Attracting Software Practitioners

- 🧑‍💻 Focused on (what we perceived to be) *industry-relevant topics*: UI testing 🧪, UI security 🔒, CI/CD pipelines 🔁
- 🎙️ Invited a *[world-class speaker](https://automationpanda.com/)* with extensive industry experience, who provided a very interesting and highly relevant virtual keynote despite the low turnout
- 📆 Hosted the event on *Saturday* to avoid potential conflicts due to work schedules
- 🗣️ *Publicized the workshop* to our [local developer group](https://nrv.dev/) Slack channel and [LinkedIn](https://www.linkedin.com/posts/activity-7323820203622998016-C_5o?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAtzWLgBdl1B9ECX-U57kWPxRdtcmPPQI7Y)
- 💻 Made the event *hybrid* to support in-person and virtual attendance
- 🍕 Provided *free food* (lunch and refreshments)

## Reflection

There are some clear issues that might have prevented attendance---a 4-hour workshop on a Saturday might be too long of a time commitment, hosting it on campus may have deterred non-academic attendees, providing compensation would have encouraged participation, etc. Here are some more takeaways on what we could do better next time.

- 📖 Research-to-Practice Relevance: I assumed our research topic (UI testing and security in CI/CD) would be relevant to software developers---and our preliminary findings from this work show it is a challenge for practitioners in open-source development [Gan2025]. However, it may not be a topic developers are actually interested in, or did not resonate with the population we reached out too. Reaching out to the target audience ahead of time to see what issues/topics they care about, then organizing our outreach based on that may be more effective. In addition, better communication regarding the direct relevance and value of the topic/our work could help.
- 📢 Broader Promotion: To promote the workshop, I shared messages on the local developer Slack channel (n = 2) and LinkedIn (n = 1), in addition to emails to relevant listservs at Virginia Tech. However, more broad and more frequent publicizing may have helped. I am also personally off most social media now, with the exception of LinkedIn. Yet, it may be beneficial to re-join social media and explore other online platforms to promote our work and engage with development-related communities. Suggestions are appreciated!
- 🤝 Deeper Relationships: Finally and most importantly, deeper connections with the target audience could enhance future efforts. This was not my first time messaging this particular group, and I have met and interacted with several members of this community before. However, establishing personal connections and more in-depth relationships can encourage engagement and motivate participation. For instance, attending events and meetup groups hosted by this organization to engage with developers through face-to-face interactions. This will also help gain insights on what our local developer community cares about, motivating future research studies and enhancing the overall relevance of our work.

We will regroup and eventually try again---planning to incorporate some of these items as we potentially explore other ways to showcase our work and help bridge the research-practice gap. Any thoughts, tips, or suggestions on how to better engage with practitioners as researchers are welcome.

## References

- [Gan2025]: X. Gan, H. Liang, C. Brown. "Challenges, Strategies, and Impacts: A Qualitative Study on UI Testing in CI/CD Processes from GitHub Developers' Perspectives". *International Conference on Software Testing, Verification and Validation* (ICST 2025).

# FSE 2025 Preview - Jun 20, 2025 - Chris Brown

The ACM International Conference on the [Foundations of Software Engineering](https://conf.researchr.org/home/fse-2025) (FSE) is one of the leading venues for software engineering-related research---targeting researchers, practitioners, and stakeholders. We're excited to share that several of our recent papers were accepted and will be presented at the main track of the conference this year (a follow-up post will highlight the workshop papers). In this post, we briefly summarize the problems explored, provide an overview of our research findings, and discuss implications from three papers that will appear in the FSE main track:

## How do Software Engineering Candidates Prepare for Technical Interviews? [FSE SEET]

Brian Bell, Teresa Thomas, Sang Won Lee, Chris Brown

- 🔍 Problem: Current tech hiring interview processes are challenging, difficult to prepare for, and rarely faced by candidates in computing curriculum and education.
- �� Study: We surveyed 131 candidates actively pursuing SE-related roles to understand how they prepare for technical interviews.
- 📊 Findings: Candidates use varied tools to prepare (mostly YouTube and LeetCode), but rarely train in authentic settings (with coding, communication, and an audience) and lack support in education---leading to increased anxiety and unpreparedness. However, candidates who practice with others (i.e., mock interviews) feel significantly more prepared than those who train alone.
- 💡 Implication: We provide implications for how candidates, employers, tech interview preparation resources, and CS education can enhance students' preparedness for technical interviews---a process necessary to obtain employment in the tech industry.

# DevCoach: Supporting Students Learning the Software Development Life Cycle with a Generative AI powered Multi-Agent System [FSE SEET]

Tianjia Wang, Matthew Trimble, Chris Brown

- 🔍 Problem: The software development lifecycle (SDLC) is critical for developing and maintaining software systems, yet challenging to effectively incorporate within learning environments. Recent work has explored leveraging generative AI to enhance SE education, but how effectively can it support learning and practical experiences for students learning SDLC concepts?
- 🧪 Study: We implemented `DevCoach`, a multi-agent system consisting of AI-powered personas representing roles in SE teams to help students learn and complete tasks related to the SDLC (e.g., requirements, design, implementation, testing, and review). We evaluated our tool with a user study with 20 students across DevCoach and baseline study settings.
- 📊 Findings: Our results show `DevCoach` demonstrated the ability to enhance student learning gains, enhanced students' completion of SDLC activities, and improved perceived aspects of learning environments grounded in the Community of Inquiry framework (social, cognitive, and teaching presence) [Garrison1999].
- 💡 Implications: We discuss the potential of generative AI and multi-agent systems in advancing SE education to offer personalized and collaborative experiences to help learners receive training on other software development concepts.

## AutoPyDep: A Recommendation System for Python Dependency Management Utilizing Graph-Based Analytics [FSE Tool Demo]

Dibyendu Brinto Bose, Travis Chan, Matthew Trimble, Chris Brown

- 🔍 Problem: Managing software dependencies is increasingly complex in modern software development---particularly in popular programming languages such as Python [Neils2024], causing frustration for programmers across varied domains.
- 🧪 Study: We implemented `AutoPyDep`, a graph-based recommendation system to support Python dependency management through various features such as centrality analysis of dependencies, visualizations for library interdependencies, and predicting the nature and timing of releases based on historical data. We conducted a preliminary evaluation to assess the prediction capabilities of our tool.
- 📊 Findings: Using a collected [dataset](https://anonymous.4open.science/r/Graph_Analysis-9D03/) of Python release notes, we found `AutoPyDep` demonstrated accurate capabilities for release type (New Features (*F1 = 0.95*), Bug Fixes (*F1 = 0.94*), Security (*F1 = 0.92*), and Performance (*F1 = 0.89*)) and date (mean error ~ 2 months) predictions.
- 💡 Implication: We briefly discuss implications and future work to enhance `AutoPyDep` and future dependency management systems.

We look forward to sharing these efforts and engaging with the research community at FSE 2025. We hope these papers---reflecting ongoing threads in our overall research---provide useful insights, and we welcome discussions, critiques, and collaborations that can extend them further. Looking forward to attending the conference and hope to see you in Trondheim, Norway next week! Also stay tuned for an upcoming post on our contributions to several of the FSE workshops.

## References

- [Garrison1999]: Garrison, D. Randy, Terry Anderson, and Walter Archer. "Critical inquiry in a text-based environment: Computer conferencing in higher education." The internet and higher education 2.2-3 (1999): 87-105.
- [Neils2024]: Niels Cautaerts. "Python dependency management is a dumpster fire". 2024. [https://nielscautaerts.xyz/python-dependency-management-is-a-dumpster-fire.html](https://nielscautaerts.xyz/python-dependency-management-is-a-dumpster-fire.html)

---

FSE 2025 Preview 2: Workshops - Jun 25, 2025 - Chris Brown

[Foundations of Software Engineering](https://conf.researchr.org/home/fse-2025) was a great opportunity to connect with and learn from software engineering researchers. In addition to the [education and tool demo tracks](https://code-world-no-blanket.github.io/blog/2025-06-20_fse25.html) of the conference, we have several contributions to co-located workshops at FSE 2025 that will be presented later this week!

## Towards Evidence-Based Tech Hiring Pipelines [SE 2030]

Chris Brown, Swanand Vaishampayan

- 🔍 Problem: Software engineers are primarily hiring through a tech hiring pipeline, consisting of processes such as resume matching and technical interviews. However, we lack insights on how to effectively evaluate the capabilities of programmers.
- �� Findings: We offer a roadmap to promote *evidence-based hiring* in the tech industry grounded in insights from evidence-based decision making---discuss challenging and future research directions to incorporate contextual, experiential, and research-based evidence into tech hiring pipelines.
- 💡 Implication: We provide implications for improving tech hiring processes, enhancing SE research on hiring, preventing toxicity and promoting diversity and inclusion in hiring processes, and promoting the adoption of evidence-based practices on software engineering in practice.

## The First International Workshop on Large Language Model-Oriented Empirical Research (LLanMER) [FSE WS]

Na Meng, Xiaoyin Wang, Chris Brown (Workshop Organizers)

- 🔍 Problem: There is fast growing interest in the application of large language models (LLMs) in software practice and research. However, lots of questions remain regarding responsible, reliable, and reproducible empirical research with LLMs.
- 💡 Workshop: Our [workshop](https://llanmer.github.io) focuses on methodologies for conducting empirical research with LLMs. We aim to provide a venue to share ideas, discuss obstacles and challenges, brainstorm solutions, and establish collaborations in LLM-oriented empirical research.

**Note:** If you were attending FSE in Trondheim 🇳🇴, please join us for our workshop on Friday from 2:00-5:30pm in the Sirius room!

## From Prompts to Properties: Rethinking LLM Code Generation with Property-Based Testing [LLanMER]

Dibyendu Brinto Bose

- 🔍 Problem: Large language models are increasingly used for code generation, however evaluating generated code is challenging and unit testing-based techniques are insufficient.
- 🧪 Study: We propose Property-Based Testing (PBT) as an alternative strategy, and conduct a preliminary evaluation using two code generation models ([StarCoder](https://huggingface.co/blog/starcoder) and [CodeLlama](https://github.com/meta-llama/codellama)) on two datasets ([MBPP](https://github.com/google-research/google-research/tree/master/mbpp) and [HumanEval](https://github.com/openai/human-eval)).
- 📊 Findings: Our results show unit test-based evaluations provide insights on correctness, while PBT is capable of evaluating against additional logical and structural constraints to assess in generated code.
- 💡 Implication: We suggest that hybrid approaches combining unit and property-based testing can provide a more reliable evaluation for LLM-generated code.

## The Evolution of Information Seeking in Software Development: Understanding the Role and Impact of AI Assistants [HumanAISE]**

Ebtesam Al Haque, Chris Brown, Thomas D. LaToza, Brittany Johnson

- 🔍 Problem: Information seeking constitutes a considerable part of software development---however, we lack insights on the impact of AI-assisted tools on software engineers' information needs and information-seeking behaviors.
- 🧪 Study: We conducted a mixed methods study, surveying and interviewing software practitioners to understand how developers use AI tools for information seeking and the impact of AI tools on productivity and skill development.
- 📊 Findings: Most participants reported using AI tools to support information seeking. We also observed challenges with AI-assisted information seeking, mixed perceptions on perceived productivity, and positive impacts expanding developer knowledge and skills.
- 💡 Implication: We discuss the evolution of information seeking behaviors in the age of AI, outlining productivity and learning trade-offs in addition to motivating future directions for AI-assisted developer tools.

## Benchmark Infrastructure for LLMs for Code (BI4LLMC)**

I was also invited to participate in the International Workshop on Benchmark Infrastructure for LLMs for Code, aiming to devise solutions to address the growing need for effective and rigorous evaluations of LLMs for coding-related tasks.

We hope the discussions at these workshops will spark new ideas, build community, and create new questions for us to explore within the evolving landscape of software engineering and SE research.