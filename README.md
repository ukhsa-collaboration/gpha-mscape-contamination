# Contamination

WIP - 
This repo is a Work in Progress. I have decided to split the previous 'contamination-data' codebase into two - 
- Python
- NextFlow
This way the Python can be separate, tested and run locally (with some helper scripts to download the data needed.) Then
once ready, it can be packaged up into a NextFlow pipeline when we know how/when we want to run it. 

## What is this code base and what is its purpose?

`Contamination` is a python-based tool that gathers, handles and plots data from the negative control samples in mSCAPE, 
and produces reports. There are summary reports and site-based reports. The reports contain a number of plots that look
at the composition of the negative controls. 

In an ideal world, these negative controls would be water or diluent, free of microorganisms. In reality, negative 
controls, when included in nucleic acod extraction and sequencing runs, tend to reflect a number of sources of microbes 
that did not originate in the samples - i.e _contamination_. 
Possible sources include:
- human (the person handling the samples)
- environment (introduced during the processes)
- reagent (kitome)
- environment (other reagents or equipment)

## Installation

Add installation instructions here. Ideally include commands to make  
the process as easy as possible for users.  

Clone repo and create environment:  
`git clone git@github.com:ukhsa-collaboration/gpha-mscape-contamination.git`  

`conda env create -n contamination `  

`conda activate contamination`  

Installation for users:  
`cd gpha-mscape-contamination`  
`pip install .`

Installation for developers (installs code in editable mode):  
`cd gpha-mscape-contamination`  
`pip install --editable '.[dev]'`

## Usage

Include command line arguments (e.g. the output displayed when using -h)  
for reference. Example commands can also be helpful.

## Other sections

Add other sections as appropriate for your repo. This may include  
instructions on updating the repo, instructions on adding new  
references, troubleshooting etc. 

