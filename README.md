# The Deliberate Reader

**A curated information ecosystem of 355 global media sources across 8 languages, 40+ countries, and 5 ecosystem layers.**

-----

## What This Project Is

The Deliberate Reader is a personal information architecture built from the premise that how you consume information is as consequential as what you consume. It is not a generic list of good media outlets. It is a scored, weighted, and structurally balanced ecosystem designed for a specific reader profile, using a reproducible methodology that anyone can adapt for their own needs.

Every source was evaluated using an eight-criterion weighted scoring system tailored to the reader’s intake profile, with a portfolio modifier that rewards ecosystem diversity and penalizes redundancy. The result is a living directory of 355 sources, each scored from 0 to 100 for profile fit, organized into five ecosystem layers: **Anchors**, **Specialists**, **Regional**, **Research**, and **Ideas**.

-----

## How It Was Built

The process followed five stages, combining structured self-assessment with AI-assisted research across three platforms.

**Stage 1: Information Intake Form** The reader completed a 30-question self-assessment covering languages, geographic priorities, disciplinary interests, trust thresholds, preferred outlet types, and explicit anti-preferences. This structured specification became the benchmark against which every recommendation was evaluated.

**Stage 2: Perplexity AI Deep Research** The intake form was submitted to Perplexity AI’s Deep Research mode, which produced a citation-grounded report of recommended outlets organized by region and topic, emphasizing outlets with published editorial standards.

**Stage 3: ChatGPT Extended Thinking Deep Research** The same intake profile was independently submitted to ChatGPT’s Extended Thinking Deep Research mode, which generated a parallel set of recommendations. This second pass caught outlets that the first had missed, particularly niche academic journals, emerging digital-native outlets, and non-English specialist sources.

**Stage 4: Claude Opus 4.6 Extended (Scoring and Synthesis)** All outputs from Stages 2 and 3, along with the reader’s existing reading lists, were consolidated and submitted to Claude Opus 4.6 for final processing. Claude deduplicated 355 unique sources, reconciled conflicting metadata, classified each outlet by type and editorial orientation, and computed the profile-specific fit score described in the Scoring Methodology section below.

**Stage 5: Editorial Review** The scored master list was reviewed for coherence, checking that the portfolio balance approximated the target distribution and that no priority region or discipline was underrepresented.

-----

## Scoring Methodology

Each source receives a base score out of 100 distributed across eight weighted criteria, followed by a portfolio modifier of up to plus or minus 15 points.

|Criterion                        |Points|What It Measures                                                                                                                      |
|---------------------------------|------|--------------------------------------------------------------------------------------------------------------------------------------|
|Trustworthiness & Method         |30    |Sourcing discipline, correction culture, editorial standards, transparency                                                            |
|Regional Depth                   |20    |Real on-the-ground intelligence for the reader’s priority geographies                                                                 |
|Disciplinary / Niche Depth       |15    |Specialist value in areas such as technology, labor, humanitarian affairs, philosophy, climate, arts, or digital humanities           |
|Pluralism Quality                |10    |Ability to represent competing views fairly without collapsing into false balance or empty centrism                                   |
|Theme Fit                        |10    |Alignment with priority themes including AI, labor/SDG 8, humanitarian systems, mapping, arts, public policy, global political economy|
|Language & Translation Usefulness|5     |Value for multilingual reading practice or translation access                                                                         |
|Signal to Noise Ratio            |5     |Density of substantive content relative to filler, opinion churn, or engagement bait                                                  |
|Format Utility                   |5     |Newsletter quality, explainer depth, archival value, suitability for daily or weekly reading                                          |

**Portfolio Modifier (plus or minus 15 points).** After computing the base score, a portfolio adjustment is applied. Points are added when a source fills an underserved geography, addresses a disciplinary gap, or increases ownership and institutional diversity through nonprofit, independent, or specialist models. Points are subtracted when a source is largely redundant with stronger outlets already in the portfolio or when it adds prestige without adding genuine perspective.

-----

## How to Build Your Own

The methodology behind The Deliberate Reader is fully reproducible. If you want to build your own curated media ecosystem, start by completing the intake form below. Your answers will define the specification that shapes every recommendation and scoring decision. Once completed, submit your answers to any combination of AI research tools (Perplexity Deep Research, ChatGPT Deep Research, Claude) and ask each platform to recommend sources aligned with your profile. Then consolidate, deduplicate, and score the results using the weighting system above, adapted to your own priorities.

### The Information Intake Form

Answer each of the following questions as specifically as possible. The more precise your answers, the more useful the resulting ecosystem will be.

**1. Main Purpose of Your News Diet**
What is the primary goal of your daily information consumption? Are you trying to stay broadly informed, build expertise in specific domains, support professional work, or some combination? Describe what success looks like for your media diet.

**2. What You Most Want to Avoid**
What types of content, framing, or editorial behavior do you want your ecosystem to minimize or exclude entirely? Consider sensationalism, clickbait, partisan spin, false balance, opinion disguised as reporting, or any other patterns you find counterproductive.

**3. What “Neutral” Means to You**
How do you define neutrality or objectivity in journalism? Do you prefer strict both-sides framing, rigorous pluralism that hosts multiple perspectives without false equivalence, or something else? Describe the editorial posture you trust most.

**4. Regions You Want Covered Regularly, in Rough Priority Order**
List the countries, regions, or areas of the world you want to follow on a daily or near-daily basis. Rank them roughly by how important regular coverage is to you.

**5. Regions You Want Beyond Headlines and with Real Depth**
Which of the regions above require more than headline-level coverage? Where do you need investigative, analytical, or specialist depth rather than just awareness?

**6. Europe Priority within Europe**
If Europe is in your list, which specific countries or subregions matter most? Consider Western Europe, Scandinavia, the Balkans, Central and Eastern Europe, the EU institutions, or specific countries.

**7. Southeast Asia Priority within Southeast Asia**
If Southeast Asia is in your list, which specific countries matter most? Consider Singapore, Malaysia, Indonesia, Vietnam, the Philippines, Thailand, Myanmar, Cambodia, or the region as a whole.

**8. Africa Priority within Africa**
If Africa is in your list, which subregions or countries matter most? Consider North Africa, West Africa, the Sahel, East Africa, Southern Africa, the Horn of Africa, or specific countries.

**9. Americas Outside North America**
If Latin America, the Caribbean, or Brazil are in your list, which specific countries or subregions matter most? Consider Central America, the Andean countries, the Southern Cone, Brazil, the Caribbean islands, or specific nations.

**10. Languages in Your Daily or Near-Daily Mix and Comfort in Each**
List every language you can read or listen to, with an honest assessment of your proficiency in each. Distinguish between languages you use daily, those you use for deliberate practice, and those you access only through translation.

**11. Time per Day**
How many minutes per day can you realistically dedicate to structured information consumption? Be honest about your actual habits, not your aspirations.

**12. Preferred Time Split**
How would you like to divide your daily reading time? For example, what percentage should go to quick scanning of headlines, to deep reading of longform or investigative work, to specialist or research sources, and to language practice?

**13. Essential Topics**
What topics must your ecosystem cover without fail? List the subjects where you need consistent, reliable coverage regardless of what else changes.

**14. Topics You Prefer from Specialist Outlets**
Which of your essential topics are best served by dedicated specialist publications rather than general-interest outlets? Where does mainstream coverage fall short for your needs?

**15. Disciplinary Lenses You Want Represented**
Beyond topic areas, what analytical frameworks or disciplinary perspectives do you want your ecosystem to include? Consider political economy, international law, science and technology studies, philosophy, environmental humanities, digital humanities, cartography, architecture, or others.

**16. Preferred Overall Mix**
What percentage of your ecosystem should come from large reputable institutions (wire services, public broadcasters, papers of record), from independent, specialist, and nonprofit outlets, and from research, academic, and official sources?

**17. Opinion/Commentary Tolerance**
How much opinion, editorial commentary, or advocacy journalism are you comfortable including in your ecosystem? Do you want it separated from reporting, mixed in, or excluded entirely?

**18. Preferred Formats**
Which formats work best for your reading habits? Consider articles, newsletters, podcasts, video, longform essays, data visualizations, interactive tools, academic journals, or curated digests.

**19. Preferred Overall Structure**
Do you want your ecosystem organized by region, by topic, by outlet type, by reading frequency, or by some combination? How do you imagine navigating it day to day?

**20. Duplication Tolerance**
How much overlap between sources are you willing to accept? Would you rather have three outlets covering the same region from different perspectives, or one strong outlet per region with the slots freed up for other geographies?

**21. Desired Source Mix**
Do you want a smaller, tightly curated ecosystem of 50 to 80 sources that you can realistically follow, or a larger reference directory of 200+ sources that you consult selectively? Or something in between?

**22. Paywall Tolerance**
How many paid subscriptions are you willing to maintain? Do you want the ecosystem to prioritize free and open-access sources, or are you comfortable with a mix of free and paid?

**23. Include Nonprofit, Academic, and Data-Journalism Outlets**
How important is it that your ecosystem includes nonprofit investigative newsrooms, academic journals, and data-journalism organizations? Should these be core components or occasional supplements?

**24. Include Official-Source Supplements**
Do you want to include primary sources from international organizations (UN agencies, WHO, IPCC, ILO, World Bank) and national statistical offices as part of your regular intake, or only for occasional reference?

**25. Traditional Chinese Balance**
If Traditional Chinese is one of your reading languages, how should it be balanced with English and other languages? Should Chinese-language sources focus on Taiwan, on Greater China comparatively, or on global coverage through a Chinese-language lens?

**26. French Balance**
If French is one of your reading languages, how should Francophone sources be balanced? Should they focus on Quebec, on France, on Francophone Africa, or on global coverage in French?

**27. Easy-Language Preference**
Are you studying any languages at an intermediate level where you would benefit from learner-friendly news sources (simplified vocabulary, furigana, slow audio, transcripts)? If so, which languages and at what level?

**28. When Do You Want Contrasting Perspectives on the Same Issue**
For which types of stories or topics is it most important to you to read the same event covered from multiple outlets, regions, or ideological positions? Where is frame comparison most valuable?

**29. Blind Spots You Especially Want Corrected**
What are the gaps in your current media diet that you are most aware of? Which regions, topics, perspectives, or types of sources are you currently missing and want this ecosystem to address?

**30. Top Optimization Priorities**
If you had to choose three qualities to optimize above all others, what would they be? Examples might include trustworthiness, geographic breadth, disciplinary depth, multilingual access, or ecosystem diversity.

-----

## Five Ecosystem Layers

Each source is classified into one of five layers, each with its own color in the directory.

**Anchors** are large, established institutions (wire services, public broadcasters, papers of record) that provide the factual baseline. They are the sources you check first to establish what happened before examining how it is framed.

**Specialists** are outlets with deep expertise in a specific domain (climate, technology, humanitarian affairs, security, labor) that go further than any generalist can. They provide the depth that anchors sacrifice for breadth.

**Regional** outlets deliver on-the-ground intelligence for specific countries, cities, or areas. They are the sources that know a place well enough to tell you what the international press is missing.

**Research** sources include academic journals, preprint repositories, international organizations, statistical offices, and data platforms. They provide the primary evidence against which claims from other layers can be verified.

**Ideas** publications are magazines, reviews, and essay platforms devoted to philosophy, political economy, arts, culture, architecture, and cross-disciplinary thinking. They provide the intellectual context that transforms information into understanding.
l

-----

## License

This project is shared for personal and educational use. The scoring methodology and curation reflect a specific reader profile and are not intended as universal quality rankings. Adapt the methodology to your own priorities.
