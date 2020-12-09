---
layout: page
title: Other projects
---

## Analysis of Antarctic Petrel Foraging Trips in the Southern Ocean

**Check out my slide presentation [here](assets/content/Petrel Presentation.pdf).**

Antarctic Petrels (*Thalassoica antarctica*) are an important Antarctic sentinel species. They often gather in large flocks on icebergs during long periods at sea, meaning that the behavior and ecology of these birds can be a useful lens to study the health of the Antarctic. However, our understanding of the ecology and life history of these birds are incomplete.

<figure>
<p align="center">
  <img src="/assets/img/petrelfly.png" width="600" align="center" alt="petrel">
</p>
</figure>

156 petrels were tagged with GPS monitors at Svarthamaren, Dronning Maud Land, the largest known colony of Antarctic Petrels in the world. These data were originally collected to test for overlap between petrel forage routes and commercial krill fisheries (<a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0156968">Descampes, S. et al. PLOS ONE, 11 (8), 2016</a>). These GPS data were made publically available on <a href="https://www.movebank.org/cms/movebank-main">Movebank</a>. I analyzed Antarctic Petrel foraging data over the austral summers of 2012-2014 for the Final project of my Avian Ecoloogy class in the spring of 2020. I plotted Petrel foraging paths, faceted by year and month. I observed high variability in foraging behavior and determined that the length of petrel forage trips were significantly different across different years.

I also clustered the Petrel foraging trips using Partitioning Around Medoids (PAM) Clustering to identify prototypical petrel foraging trips during different years. To determine possible causes of this variability, I visualized the pretrel foraging trips in light of remote sensing data, corresponding to various environmental variables like sea surface temperature, bathymetric depth, net primary production, locations of large icebergs, and sea ice cover. After integrating these data, I identified a phenomenon where petrels tended to forage in regions of low to moderate sea ice cover (<50% cover), a threshold that corresponds to the sea ice edge.

<figure>
<p align="center">
  <img src="/assets/content/Prototypes_plot.png" width="800" align="center">
</p>
</figure>                                                                                       

This finding was supported by the scientific literature (<a href="https://royalsocietypublishing.org/doi/full/10.1098/rsos.191429">Delord, K. et al., R. Soc. Open Sci. 7, 2020</a>). Exploratory plots indicated that lower sea ice cover corresponded to higher Net Primary Production, providing ecological justification for this phenomenon. This project represented a data-driven approach to understand the ecology of an important Antarctic sentinel species.

## Simulating DIII National Cross Country Meets

**Check out our slide presentation [here](assets/content/Math154-FinalProject-Slides.pdf)**
**Check out our <a href="https://n8stringham.shinyapps.io/CrossCountry_Simulator/">shiny app simulator</a> for this project.**

I am a Division III Cross Country runner, and much of my time outside of class is spent training 75 miles a week to compete in long distance Cross Country and Track races. Long distance running is notoriously difficult to predict, because performance is highly stochastic and races are influenced by many factors: weather, health, level of competition, etc.

In the running world, athletes spend a lot of time predicting race outcomes and analyzing past races to understand what individuals/teams are favorites, and which teams over/underperform relative to expectations. Along with my classmates and teammates <a href="https://github.com/tedtonks87">Daniel Rosen</a> and <a href="https://github.com/n8stringham">Nathan Stringham</a>, we took a data-driven approach to this problem, which could provide useful information for evaluating coaches and providing information to recruits.

We scraped publically availble race data over the 2018 and 2019 cross country seasons off of <a href="https://www.tfrrs.org/">TFRRS</a> and adjusted the race times based on course difficulty. Then we modeled each individual athlete's performance using a normal distribution, and drew random times for each athlete. Then times for every runner at the national meet were ranked, simulating a virtual race. Team scores were computed by the place of the top 5 runners, and teams were ranked based on these scores.

Our simulated results indicated the competitive landscape for each year. Teams were classified as overperformers or underperformers based on how many points they beat their expected simulated score by, and how likely they were to beat that score based on empirical probabilities. Carleton and Pomona-Pitzer (my team!) were found to be overperformers over those two seasons, while Carnegie-Mellon profoundly underperformed over those two seasons.

This was an especially poigniant project for me, since I got the opportunity to run at the 2019 NCAA DIII National Cross Country Meet. At the meet, I helped our team capture the first national championship in school history. Check out the picture of the victorious Sagehens!

## Tracking Historical Corn Consumption by Sandhill Cranes in the Eastern Flyway

In the spring of 2020, I wrote a mock grant proposal to use isotopic (C13) ratios in museum specimens of Sandhill Cranes from the Eastern Flyway to measure temporal trends in corn consumption by this once endangered avian species. This represented a well-researched and thoughtfully-concieved approach to leveraging museum specimens for interesting historical ecology research. Additionally, as climate change affects the agriculture of the American Heartland, this project could be useful for projecting the impacts on this important species. Check out my proposal [here](assets/content/Avian Proposal Final.pdf).

## UCLA Datafest 2019: Travel and Player Fatigue on the Candian National Women's Rugby 7's Team

In collaboration with several classmates, I attended UCLA Datafest in the Spring of 2019, where we won the Best Use of External Data Award for scraping Twitter Data to determine when the Canadian National Rugby team was traveling for competition. Then we created a metric for fatigue, incorporating a number of variables, and saw that this metric tended to spike immediately following travel trips. We contended that this work may encourage the team to invest in more recovery to maximize the performance of their athletes. Check out our (silly!) presentation [here](assets/content/B11_FlockOfSQLs.pdf).


