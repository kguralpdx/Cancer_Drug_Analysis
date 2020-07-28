# Cancer Drug Regimens' Performance on Mouse Tumors

## Overview

A study for potential treatments for squamous cell carcinoma (SCC), or a commonly occurring form of skin cancer, was conducted on 249 mice with SCC tumor growth. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of a drug of interest, Capomulin, versus the other treatment regimens.

## Observations and Insights

After reviewing the data and creating the various plots, I have made the following observations:

* The weight of a mouse has a strong positive correlation with the average volume of its tumor.
* Capomulin was effective in shrinking tumor volume. There were a few periods in which the tumor increased even when using the drug, but the increase was minimal and followed by a period with a larger decrease in tumor volume.
* The role gender played in the results needs further analysis. There was a pretty even mix of male and female mice in the study, however, how many mice of each gender were given each drug was not analyzed.

## Tasks

To generate all of the tables and figures needed for the technical report of the study as well as a top-level summary of the study results.

#### Files

All the files for this analysis can be found in the **Pymaceuticals** folder. The data source files are in the **data** subfolder in that Pymaceuticals folder.

* **Jupyter Notebook** (Pymaceuticals/pymaceuticals_starter.jpynb) - The Jupyter Notebook file that contains the scripts and results
* [Mouse Data](Pymaceuticals/data/Mouse_metadata.csv) - this file contains details about each mouse in the study
* [Study Results Data](Pymaceuticals/data/Study_results.csv) - this file contains the study results used for the analysis


## Notes

Some of the x-axis functionality seemed temperamental; sometimes it worked and other times it would cause an error. Those have been commented out in the jupyter notebook.

One mouse had multiple entries for the same timepoints so that mouse was removed from the analysis data making the total mouse count 248.