# Attention and driving

This is a repository holding information on papers that were used for writing the report on ["Behavioral research and practical models of drivers' attention"](https://arxiv.org/pdf/2104.05677.pdf). The repository contains ~200 behavioral and ~100 practical papers published since 2010 where drivers' gaze allocation is explicitly measured (e.g. via an eye-tracker) or used in some relevant practical application (e.g. driver monitoring).


# Links to data

* [Behavioral research](https://ykotseruba.github.io/attention_and_driving/behavioral_studies.html)
* [Practical research](https://ykotseruba.github.io/attention_and_driving/practical_scene_gaze.html)
* [Datasets](https://ykotseruba.github.io/attention_and_driving/datasets_datasets.html)
* [Surveys](https://ykotseruba.github.io/attention_and_driving/surveys_surveys.html)

## Behavioral research

Papers and their descriptions are split into three tables: Studies, Factors and Eye-tracking measures


### Studies

For each study the following information is provided:

* Reference: use this to search for bibtex information in `bibtex/behavioral.bib`
* Paper: title, venue, year
* Dataset: name of the dataset or NDS used in the study
* Experiment duration: usually it is the entire duration of the study including any pre- or post-experiment procedures. The actual driving time may be shorter than the specified duration.
* Number of subjects (whose data was used for analysis)
* Eye tracker type, model and sampling rate
* Driving simulator model (if applicable)
* Recording conditions: in driving simulator (low, medium or high fidelity), or on-road (naturalistic, directed, closed track)
* Vehicle control: active or passive

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

Papers and their descriptions are split into 6 tables: 5 types of Applications and Factors


### Applications

Papers are split into 5 categories:

* Gaze prediction outside vehicle
* Gaze prediction inside vehicle
* Inattention detection
* Driver awareness
* Self-driving

For each paper the following information is provided:

* Reference: to be used for searching for bibtex information in `bibtex/practical.bib`
* Paper: title, venue, year
* Code: link if available
* Input, observation length, output
* Dataset: custom or one of the datasets listed in datasets
* Evaluation metrics


### Factors

See [factors](#behavioral_factors) defined for behavioral studies.


## Surveys and meta-reviews


A list of relevant surveys and meta-reviews with:

* Reference: to be used for searching for bibtex information in `bibtex/surveys.bib`
* Paper: title, venue, year
* Topic: a major topic of the survey or meta-review

## Datasets

The table lists datasets (with and without eye-tracking data), naturalistic driving studies and field operational tests, and their properties:

* Reference: to be used for searching for bibtex information in `bibtex/practical.bib`
* Paper: title, venue, year
* Dataset name (full and abbreviated)
* Link to data (if available)
* Data types (e.g. video, CAN bus data)
* Annotations (e.g. bounding boxes, text)
* Recording conditions
* Vehicle control: passive or active
* Number of subjects whose gaze was recorded or who drove the vehicle if no gaze data is available
* Number of frames, videos, cameras


## Contribute to this project

If you would like to provide corrections or suggest missing papers, please post an issue on this github.

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

- March 31, 2021: The repository is up
- May 19, 2021: Switched from Google Spreadsheets to Tabulator


