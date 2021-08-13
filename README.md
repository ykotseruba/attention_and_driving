# Attention and driving

This repository contains a curated list of papers and meta-data that were used for writing the report on ["Behavioral research and practical models of drivers' attention"](https://arxiv.org/pdf/2104.05677.pdf). 

The list contains papers published from **2010** to **mid-2021** where drivers' gaze allocation is explicitly measured (e.g. via an eye-tracker) and analyzed, or where gaze data is used in driving-related practical applications (e.g. driver monitoring):

* **~250** behavioral studies 
* **~110** models
* **~30** datasets
* **~100** surveys and relevant papers

The repository will be regularly updated with new papers.


# Data in interactive tables

* [Behavioral research](https://ykotseruba.github.io/attention_and_driving/behavioral_studies.html)
* [Practical research](https://ykotseruba.github.io/attention_and_driving/practical_scene_gaze.html)
* [Datasets](https://ykotseruba.github.io/attention_and_driving/datasets_datasets.html)
* [Surveys](https://ykotseruba.github.io/attention_and_driving/surveys_surveys.html)

*Note: double-click on the cell in any table to copy its contents or select text normally by clicking and dragging.*

# Data in Excel spreadsheets
Download from the `spreadsheets` folder.

# What is in the tables

## Behavioral research

Papers and their descriptions are split into three tables: Studies, Factors and Eye-tracking measures

### Studies

For each study the following information is provided:

* **Reference:** link to the paper
* **Bibtex:** bibtex information
* **Paper:** title, venue, year
* **Dataset:** name of the dataset or NDS used in the study
* **Experiment duration:** usually it is the entire duration of the study including any pre- or post-experiment procedures. The actual driving time may be shorter than the specified duration.
* **Number of subjects** (whose data was used for analysis)
* **Eye tracker** type, model and sampling rate
* **Driving simulator model** (if applicable)
* **Recording conditions:** in driving simulator (low, medium or high fidelity), or on-road (naturalistic, directed, closed track)
* **Vehicle control:** active or passive

<a name="behavioral_factors"></a>
### Factors

We identified independent variables in each study and grouped them into 7 factors listed below:

* Primary (driving) task
* Secondary (non-driving) task
* Driving experience
* Demographics
* Inattention
* Environment
* Automation


### Eye-tracking measures

* Position (duration and dispersion)
* Numerosity
* Latency/distance
* Movement
* Data type: raw eye-tracker data or pre-processed data (fixations, glances)


## Practical research

Papers and their descriptions are split into 7 tables: 6 types of Applications and Factors

### Applications

Papers are split into 6 categories:

* Gaze prediction outside vehicle
* Gaze prediction inside vehicle
* Inattention detection
* Action anticipation
* Driver awareness
* Self-driving

For each paper the following information is provided:

* **Reference:** link to the paper
* **Bibtex:** bibtex information
* **Paper:** title, venue, year
* **Code:** link if available
* **Input, observation length, output**
* **Dataset:** custom or one of the datasets listed in datasets
* Evaluation **metrics**


### Factors

Same as [factors](#behavioral_factors) defined for behavioral studies.


## Surveys, meta-reviews and relevant studies


A list of surveys, meta-reviews and other relevant studies:

* **Reference:** link to the paper
* **Bibtex:** bibtex information
* **Paper:** title, venue, year
* **Topic:** a major topic of the study

## Datasets

The table lists datasets (with and without eye-tracking data), naturalistic driving studies and field operational tests, and their properties:

* **Reference:** link to the paper
* **Bibtex:** bibtex information
* **Paper:** title, venue, year
* **Dataset** name (full and abbreviated)
* **Link** to data (if available)
* **Data types** (e.g. video, CAN bus data)
* **Annotations** (e.g. bounding boxes, text)
* **Recording conditions** (for gaze data recording)
* **Vehicle control:** passive or active
* **Number of subjects** whose gaze was recorded or who drove the vehicle if no gaze data is available
* **Number of frames, videos, cameras**


## Contribute to this project

If you would like to provide corrections or suggest papers to add, please raise an issue or email '''yulia_k@eecs.yorku.ca'''.

## Cite

If you used this repository or the report in your research, please cite:

```
@article{2021_arXiv_Kotseruba,
author={Kotseruba, Iuliia and Tsotsos, John K.},
title={Behavioral research and practical applications of drivers' attention},
year={2021},
journal={arXiv:2104.05677}
}
```

### Acknowledgment

This work is greatly inspired by the [database for vision-based action prediction](https://github.com/aras62/vision-based-prediction) created by [Amir Rasouli](https://github.com/aras62).

## Updates

- August 11, 2021: Added bibtex info to practical works, added action anticipation
- August 6, 2021: Added 60 behavioral and practical works up to mid-2021. Added hyperlinks for papers and code.
- May 19, 2021: Switched from Google Spreadsheets to Tabulator
- March 31, 2021: The repository is up


