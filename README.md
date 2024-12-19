# CANDOR corpus processing and analysis  
  
This repository contains code to process and analyse data in the multimodal CANDOR corpus.  
  
The descrption of the dataset can be found here: [Andrew Reece et al. ,The CANDOR corpus: Insights from a large multimodal dataset of naturalistic conversation. Sci. Adv.9,eadf3197(2023)](https://www.science.org/doi/10.1126/sciadv.adf3197). Please cite this paper when using CANDOR in your research. 

The CANDOR corpus can be downloaded from the official [download page](https://betterup-data-requests.herokuapp.com).  You need to store the files locally in order to use the code in this reposotory.

This code is a result of the analyses on the CANDOR corpus and aims to helps others make better use of this excellent resource. Please mention this repository if you have used it in your research.

Author: [Teodora Vuković](https://www.liri.uzh.ch/en/aboutus/Teodora-Vuković.html).

## Content of the repository

[candor_process_dir.ipynb](candor_process_dir.ipynb) - extract interview files from the original nested directory structure in a single directory with a flat structure; change filenames for easier handling; change the content od the features files 
[multimodal_candor_analysis.ipynb](multimodal_candor_analysis.ipynb) - exploration and analysis of CANDOR corpus files
[stanza_candor_analysis.ipynb](stanza_candor_analysis.ipynb) - annotation of the CANDOR transcripts using Stanza language models and analysis using the annotated corpus files

