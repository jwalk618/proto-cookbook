# Anna's Prototype Cookbook

<img src="thumbnails/thumbnail.png" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook covers the genesis, evolution, intensification, and impact of Helene on the West Coast and Panhandle of Florida from a meteorological perspective.

## Motivation

This cookbook helps me actualize an idea into a mini research project. It's helping me learn how to organize a code development project, create a website formatted project pythia research report, and find/download/use datasets to plot particular parameters to tell a part of a larger story with my group. 

## Authors

[Anna Walker](https://github.com/aw618856/proto-cookbook)

### Contributors

<a href="https://github.com/ProjectPythia/cookbook-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/cookbook-template" />
</a>

## Structure

(This cookbook is broken up into two main sections - "Helene's Genesis and Intensification" and "Impacts of Storm Surge on Florida"

### Section 1 "Helene's Genesis and Intensification"

This section begins with plotting the IBTrACS of Helene which displays its path and intensification. For contextualization of the environment that spawned its genesis, the sea surface temperatures, steering flow and winds at 200hPa (jetstream), and the IR/Visible GOES-16 were plotted to follow Helene's week long evolution across the Gulf. 

### Section 2 "Impacts of Storm Surge on Florida"

While an unprecedented and extreme impact was felt further north by flooding in the Appalachian Mountains, Florida's West Coast and Big Bend region undeniably felt negative impacts from Helene's storm surge. This notebook delves into the intricacies of why Florida's West Coast is arguably the most vulnerable to storm surge in the United States, as well as qualtifies these impacts with tide gauges (thinking of adding another dataset). 

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
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/cookbook-example` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
