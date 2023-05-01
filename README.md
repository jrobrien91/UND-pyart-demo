# UND Tools of the Trade Py-ART Demo Cookbook

This ARM Cookbook covers a demonstration on the ARM Python Radar Toolkit (Py-ART) and Radar Open Science

## Motivation

University of North Dakota's Atmospheric Science Department hosts *'Tools of the Trade'*, a hack-a-thon style seminar to introduce useful topics to students research

This cookbook will introduce Py-ART, showcase input/displaying NEXRAD data from an Amazon bucket, and gridding of Py-ART radar objects

Additonal aim of this cookbook is to introduce the students to the world of open radar science

## Authors

[First Author](@first-author), [Second Author](@second-author), etc. *Acknowledge primary content authors here*

### Contributors

<a href="https://github.com/jrobrien91/UND-pyart-demo">
  <img src="https://github.com/jrobrien91/UND-pyart-demo" />
</a>

### Notebook 1 (Introduction - Why Py-ART?)
- Background on the creation and purpose of Py-ART
- Py-ART Data object
### Notebook 2 (Py-ART Basics)
- Reading NEXRAD data from the Amazon S3 bucket
### Notebook 3 (Py-ART Gridding)
- Gridding the Py-ART object
### Notebook 4 (Additional Radar Packages)
- Quick introduction / reference to additional open science radar packages

### Running on Your Own Machine
If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/jrobrien91/UND-pyart-demo` repository:

   ```bash
    git clone https://github.com/jrobrien91/UND-pyart-demo
    ```  
1. Move into the `notebooks` directory
    ```bash
    cd notebooks
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate und-tools-trade
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
