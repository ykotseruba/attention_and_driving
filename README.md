# Attention and driving

This is a repository holding information on papers that were used for writing the report on ["Behavioral research and practical models of drivers' attention"](https://arxiv.org/pdf/2104.05677.pdf). The repository contains ~200 behavioral and ~100 practical papers published since 2010 where drivers' gaze allocation is explicitly measured (e.g. via an eye-tracker) or used in some relevant practical application (e.g. driver monitoring).


## Behavioral research

Papers and their descriptions are split into three sheets: Studies, Factors and Eye-tracking measures

[Google Sheets Link](https://docs.google.com/spreadsheets/d/1nWf1auJXwuTzqlPnrK-8iOSnaogphLCCvS3QRrcU4S0/edit?usp=sharing)


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
* Intattention
* Environment
* Automation


### Eye-tracking measures

* Position (duration and dispersion)
* Numerosity
* Latency/distance
* Movement
* Data type: raw eye-tracker data or pre-processed data (fixations, glances)


## Practical research

Papers and their descriptions are split into 6 sheets: 5 types of Applications and Factors

[Google Sheets Link](https://docs.google.com/spreadsheets/d/1FkT1hz1GQv3waICiCCxWpAByB8kzOpKrAZAhbUwriyo/edit?usp=sharing)

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

[Google Sheets Link](https://docs.google.com/spreadsheets/d/1RQ1iqhZNFuJLIGquEGEh2PW7ugQdtcwJx8dU8JX_DpI/edit?usp=sharing)

A list of relevant surveys and meta-reviews with:

* Reference: to be used for searching for bibtex information in `bibtex/surveys.bib`
* Paper: title, venue, year
* Topic: a major topic of the survey or meta-review

## Datasets

[Google Sheets Link](https://docs.google.com/spreadsheets/d/1eVNaqn2RtDFQYhKi2BAluxjwI5TMkrGad52X9aSTMgU/edit?usp=sharing)

The spreadsheet lists datasets (with and without eye-tracking data), naturalistic driving studies and field operational tests, and their properties:

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

This work is greatly inspired by the database for vision-based action prediction created by Amir Rasouli.

## Updates

- March 31, 2021: The repository is up


