<img src="CFC_logo.PNG" alt="thumbnail" width="300"/>

# Caribbeans for Climate: Understanding extreme weather variability in the Caribbean region Cookbook

[![nightly-build](https://github.com/ProjectPythia/CFC-extreme-weather-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/CFC-extreme-weather-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/CFC-extreme-weather-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/813816008.svg)](https://zenodo.org/badge/latestdoi/813816008)

This Project Pythia Cookbook covers exploring extreme weather variability in the atmosphere and ocean using CMIP6 data.

## Motivation

Extreme weather events, both atmospheric and oceanic, are increasing in frequency and intensity as a consequence of anthropogenic warming. The processes responsible for such events and their impacts on Caribbean lives remain to be well understood. Our Caribbeans for Climate community (a community of Caribbean-identified climate scientists, oceanographers, and practitioners) have created a cookbook analyzing Caribbean atmospheric and oceanic extreme weather variability using Coupled Model Intercomparison Project Phase 6 (CMIP6) data. In this notebook, we execute basic statistical analysis to investigate the linkages between extreme atmospheric and oceanic heat-related events and the possible causes behind them.

#### Acknowledgements
We would like to especially thank [Justus Magin](https://github.com/keewis) for his technical support. Without his expertise we could not have been able to efficiently run the extreme SSTs notebook.

## Authors

[Jhordanne Jones](github/jhordannej), [Shanice Bailey](github/shanicetbailey), [Caribbeans For Climate community](https://www.caribbeansforclimate.com/).

### Contributors

<a href="https://github.com/ProjectPythia/CFC-extreme-weather-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/CFC-extreme-weather-cookbook" />
</a>

## Structure

_This cookbook has three sections: "Extreme SSTs" and "Extreme Precipitation" and "Links between atmosphere, ocean and ENSO"._

### Section 1: Extreme SSTs 

(Add content for this section, e.g., "The foundational content includes ... ")

### Section 2: Precipitation extremes using HighResMIP

In this notebook, we'll examine precipitation extremes using the HighResMIP data. We'll do the following:
- Making subregional-scale plots with the HighResMIP
- Plot spatial maps of linear trends in summertime environmental variables
- Calculate a seasonal indicator of tropical cyclogenesis

### Section 3: Links between atmosphere, ocean and ENSO

(Add content for this section, e.g., "Example workflows include ... ")

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/CFC-extreme-weather-cookbook.git` repository:

   ```bash
    git clone https://github.com/ProjectPythia/CFC-extreme-weather-cookbook.git
   ```

1. Move into the `notebooks` directory
   ```bash
   cd notebooks/
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate CFC-extreme-weather-cookbook
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
