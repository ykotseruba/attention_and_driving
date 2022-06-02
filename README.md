# Attention and driving

This repository contains a curated list of papers and meta-data that were used for writing the report on ["Behavioral research and practical models of drivers' attention"](https://arxiv.org/pdf/2104.05677.pdf). 

The list contains papers published from **2010** to **mid-2021** where drivers' gaze allocation is explicitly measured (e.g. via an eye-tracker) and analyzed, or where gaze data is used in driving-related practical applications (e.g. driver monitoring):

* **~250** behavioral studies 
* **~160** models
* **~35** datasets
* **~100** surveys and relevant papers# Attention and driving

This is a repository holding information on papers related to attention and driving. The repository contains behavioral and practical papers published since 2010 where drivers' gaze allocation is explicitly measured (e.g. via an eye-tracker) or used in some relevant practical application.

Excluded from the list are: 

1) studies using modes of transportation other than cars (e.g. bicycles, motorcycles, trucks, buses, trains);
2) studies that rely *only* on indirect methods to assess drivers' attention (e.g. ego-vehicle sensor information);
3) studies that focused on drivers with medical issues or under the influence of alcohol or drugs;
4) uncited papers over *5* years old.


Papers in the repository are grouped into behavioral, appliation (split into 5 application categories), datasets, and other (includes surveys and other relevant papers). For each paper listed we provide citation in bibtex format and tags. For application papers we provide information on what dataset they used (*private* if data was unpublished or link to public dataset(s)). For dataset papers we provide a short summary of the dataset and available annotations.

- [Behavioral papers](behavioral.md) - theoretical analysis of drivers' attention
- Application papers - modeling or detection of drivers' attention for assistive and autonomous driving applications:
	- [Modeling scene gaze](scene_gaze.md) - models that predict where the driver might look in the traffic scene
	- [Detecting in-vehicle gaze](in-vehicle_gaze.md) - models for detecting what area inside the vehicle the driver is looking at
	- [Detecting driver distraction](distraction_detection.md) - models for detecting manual, visual, and cognitive distractions
	- [Detecting driver drowsiness](drowsiness_detection.md) - models for detecting driver drowsiness and fatigue
	- [Driver action anticipation](action_anticipation.md) - models that anticipate drivers' maneuvers using gaze and vehicle information
	- [Driver awareness estimation](driver_awareness.md) - models that project drivers' gaze onto objects in the traffic scene
	- [Attention for self-driving](self-driving.md) - models that use attention mechanisms for automated driving
- [Datasets](datasets.md) - a list of datasets with attention-related annotations


## Contributing to this project

If you notice any errors or missing papers, please post an issue on this github.

## Citation

If you used this repository in your research, please cite:

```
@article{kotseruba2021behavioral,
  title={Behavioral Research and Practical Models of Drivers' Attention},
  author={Kotseruba, Iuliia and Tsotsos, John K},
  journal={arXiv preprint arXiv:2104.05677},
  year={2021}
}

```

### Acknowledgment

This work is greatly inspired by the database for vision-based action prediction created by [Amir Rasouli](https://github.com/aras62/).

## Updates

- June 2, 2022: restructured the tables into lists, old version is available in previous branch
- November 7, 2021: Added 50+ practical papers, restructured and cleaned up the tables
- August 11, 2021: Added bibtex info to practical works, added action anticipation
- August 6, 2021: Added 60 behavioral and practical works up to mid-2021. Added hyperlinks for papers and code.
- May 19, 2021: Switched from Google Spreadsheets to Tabulator
- March 31, 2021: The repository is up

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

Papers are split into 7 categories:

* Gaze prediction outside vehicle
* Gaze prediction inside vehicle
* Distraction detection
* Drowsiness detection
* Action anticipation
* Driver awareness
* Self-driving

For each paper the following information is provided:

* **Reference:** link to the paper
* **Bibtex:** bibtex information
* **Paper:** title, venue, year
* **Code:** link if available
* **Input, observation length, output**
* **Dataset:** custom or one of the datasets listed in datasets and data properties
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

- November 7, 2021: Added 50+ practical papers, restructured and cleaned up the tables
- August 11, 2021: Added bibtex info to practical works, added action anticipation
- August 6, 2021: Added 60 behavioral and practical works up to mid-2021. Added hyperlinks for papers and code.
- May 19, 2021: Switched from Google Spreadsheets to Tabulator
- March 31, 2021: The repository is up


