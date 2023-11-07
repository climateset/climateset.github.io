---
layout: default
---

<h1>This website is currently under development!</h1>
<div>
    <a>The links to the code and the dataset will be published at the start of December 2023.</a>
</div>

<div style="display: flex; align-items: flex-start;">
  <img src="climateset_icon.png" alt="ClimateSet Icon" style="height: 200px; margin-right: 20px;" />
  <div>
    Climate models are critical tools for analyzing climate change and projecting its 
    future impact. The machine learning (ML) community has
    taken an increased interest in supporting climate scientists’ efforts on various tasks
    such as climate model emulation, downscaling, and prediction tasks. However, 
    traditional datasets based on single climate models are limiting. We thus present 
    ClimateSet — a comprehensive collection of inputs and outputs from 36 climate models 
    sourced from the Input4MIPs and CMIP6 archives, designed for large-scale ML applications.
  </div>
</div>

# Overview
![ClimateSet Overview](./climate_set_overview.png)
1. **ClimateSet builds on the Input4MIPs and CMIP6 datasets** made available through multiple climate modeling teams on the Earth System Grid Federation (ESGF) servers.
2. **ClimateSet consists of a preprocessed, ML-ready core dataset** that includes inputs and outputs for 5 SSP scenarios, 4 forcing agents, 2 climatic variables (temperature and precipitation), for a set of 36 climate models. It is currently made publicly available through the Digital Research Alliance of Canada.
3. **The core dataset can be extended** to include different variables, height levels, ensemble members, scenarios, and any other information made available from climate models on the CMIP6 server of ESGF. The downloader and preprocessing pipelines are available on our GitHub repository.
4. **Potential use cases for ClimateSet** range from climate projection to climate data downscaling, extreme weather prediction in different warming scenarios, to large ML climate models.
5. **The main tools** provided through ClimateSet are the downloader and the preprocesser to make the climate model data consistent with each other.

*The 3D Earth System Model visualization was created by Boris Sakschewski, used with permission.*

# Ethics Statement

# Authors

