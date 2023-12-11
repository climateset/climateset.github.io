---
layout: default
---

<h1>This website is currently under development!</h1>
<div>
    <b>The links to the code and the dataset will be published in December 2023. Feel free to reach out to julia[dot]kaltenborn[at]mail[dot]mcgill[dot]ca to get prior access to the data.</b>
</div>
<br>


<!-- <div style="display: flex; align-items: flex-start;">
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
</div> -->

<div style="display: flex; align-items: stretch;">
  <div class="icon-wrapper">
    <img src="climateset_icon.png" alt="ClimateSet Icon" class="climate-icon" />
  </div>
  <div style="flex-grow: 1; display: flex; flex-direction: column; justify-content: center">
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

# Related Work
![ClimateSet Related Work](./AIWeatherClimateFigure.png)
Depending on your specific task, there might be other datasets that are more suitable for you. We are providing a list of different climate model datasets and tools here that might be helpful to you. Feel free to reach out to us if you think there is a dataset or ML model that is missing in our figure. (We are only including datasets and ML models that operate on a global scale, using reanlysis or climate model data).

## Tools
- [xMIP](https://github.com/jbusecke/xMIP): Preprocessing tool for CMIP6 data; great start to engineer your own pipelines
  
## Datasets
- [ClimateLearn](https://arxiv.org/abs/2307.01909) Accessible, large-scale weather data + 2 climate models, PyTorch package; especially suitable when looking for dataset + ML models
- [ClimSim](https://arxiv.org/abs/2306.08754) High-resolution, large-scale, accessible ML-ready dataset for 1 climate model; especially suitable for hybrid physics-ML emulation tasks
- [ClimateBench](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021MS002954) Accessible, ML-ready climate dataset for 1 climate model (NorESM)
- [WeatherBench](https://arxiv.org/abs/2002.00469) Large-scale, accessible, ML-ready weather dataset


# Ethics Statement

# News


