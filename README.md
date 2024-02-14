# DO-Intro-to-DataViz-KDrama
The final project for the Domestika course on Introduction to Data Visualisation using a data scraping plugin and [Tableau Public](https://public.tableau.com/app/profile/mariana.mayumi.hiroki.tamashiro/viz/Domestica_Visualisation_BestKDramas_2024/Sheet2?publish=yes).

## Introduction/Context: ##

- Korean dramas (K-dramas) have garnered significant international attention due to factors such as the global popularity of K-pop music and their availability on streaming platforms like Netflix.
- With their concise format and diverse themes, K-dramas have become immensely popular, often influencing future series launches.
- The project aims to analyze the popularity of K-dramas on Netflix by examining episode reviews on the IMDB website.

## Objectives: ##

- Showcase data scraping, analysis, and visualization skills using [Tableau Public](https://public.tableau.com/app/profile/mariana.mayumi.hiroki.tamashiro/viz/Domestica_Visualisation_BestKDramas_2024/Sheet2?publish=yes).
- Identify Popular Trends: Explore recurring themes, character archetypes, and narrative structures in K-dramas to inform content creation and programming decisions.
- Support Marketing Strategies: Gain insights into viewer preferences to tailor marketing strategies and audience targeting efforts for K-drama content.

## Data Collection and Analysis: ##

- Utilized a data scraping plugin to collect episode details from the best K-dramas on Netflix, sourced from the [Collider website](https://collider.com/best-korean-dramas-on-netflix/) list, updated on 27.01.2024.
- Scraped episode data from the IMDB website using the [Instant Data Scraper Google Chrome Plugin](https://chromewebstore.google.com/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah).
- Conducted data cleaning and structuring, followed by z-score calculation ((Ep Score-Mean)/Standard Deviation) for standardized comparison.
- Used the Heatmap for the first visualisation, therefore it easily shows the least popular shows, while others have good reviews throughout the whole show, bad endings or start.
  <img width="379" alt="image" src="https://github.com/marianahiroki/DO-Intro-to-DataViz-KDrama/assets/110165879/17d0ec2d-2d4c-42fa-90fc-8eff797d42ca">

- Employed other visualizations as interactive charts in Tableau to analyze episode reviews and voting trends.
  <img width="990" alt="image" src="https://github.com/marianahiroki/DO-Intro-to-DataViz-KDrama/assets/110165879/4e014689-c4d2-420b-a90f-b29b029b436f">
  <img width="991" alt="image" src="https://github.com/marianahiroki/DO-Intro-to-DataViz-KDrama/assets/110165879/b19cc123-4333-4c8b-8e89-10f2749ef84e">



## Key Learnings/Insights: ##

- Despite "King the Land" receiving limited positive feedback in its initial episodes, it garnered a significant number of votes, akin to the acclaimed "Squid Games." Further inquiry is needed to discern its unexpected success, especially considering its absence from my Netflix recommendations. [Sheet 3](https://public.tableau.com/app/profile/mariana.mayumi.hiroki.tamashiro/viz/Domestica_Visualisation_BestKDramas_2024/Sheet3?publish=yes
- "Kingdom" and "All Of Us Are Dead" share a zombie theme and maintain comparable voting numbers throughout their seasons. However, "Kingdom" boasts superior overall ratings, potentially attributed to its resonance with diverse audience demographics.[Sheet 4](https://public.tableau.com/app/profile/mariana.mayumi.hiroki.tamashiro/viz/Domestica_Visualisation_BestKDramas_2024/Sheet4?publish=yes
- While "Sweet Home" and "Hellbound" may not boast stellar reviews, they rank third in terms of votes alongside "It's Okay Not to Be Okay," which enjoys substantially better acclaim.
- "Strong Girl Nam-Soon" commenced with modest ratings but concluded poorly. Both visualizations ([Sheets 2 and 3](https://public.tableau.com/app/profile/mariana.mayumi.hiroki.tamashiro/viz/Domestica_Visualisation_BestKDramas_2024/Sheet2?publish=yes) underscore the significance of the final episode in shaping overall viewer perception.

## Impact/Results: ##

- The analysis provided valuable insights into viewer preferences, potentially guiding content creation and marketing strategies for streaming platforms like Netflix.
- Enhanced Understanding of Viewer Preferences: Insights gained can inform future content creation efforts to better meet audience expectations.
- Increased Revenue and Market Share: Findings could lead to increased revenue and market share for streaming platforms by delivering content that resonates strongly with audiences.


## Challenges and Solutions: ##

- Limitations in visualizing all 32 K-drama series due to colour palette constraints and data volume.
- Addressed by filtering unrelated or non-competing series and exploring alternative visualization techniques.


## Future Steps/Recommendations: ##

- Consider additional data sources beyond IMDB for comprehensive analysis.
- Further analysis of main themes, release dates, and actors could provide deeper insights into K-drama popularity.
- Explore alternative visualization methods and data filtering strategies to address current limitations and enhance analysis comprehensiveness.
