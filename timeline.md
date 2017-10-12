# Project Timeline for Mind-typing - v1

## Overview

Locked in patients currently are unable to communicate their needs, thoughts and feelings due to complete body paralysis and speech paralysis. Currently, nurses and healthcare workers have to guess the needs of these patients which leads to much frustration on both parties. We would like to explore the development of a BCI interface to tap into the EEG signals of such patients to control a keyboard software in order for them to type out their intention using available headsets like neurosky and Emotiv. Processing and analysis of signals to map to specific thoughts like “up, down, left, right and enter” will be implemented.

## Project Outline

### Evaluate and Research

#### Time Requirement:

2 weeks (4 days)

#### Tasks:

* Go through tutorials about OpenBCI Cyton Board
* Test connectivity between Cyton Board and Dongle
* Test pin cabling with electrodes
* Test extra channels with Daisy Module
* Test EEG activities against OpenBCI GUI


### Data Collection and Analysis

#### Time Requirement:

2 weeks (4 days)

#### Tasks:

* Test connectivity with OpenBCI Python SDK
* Capture streaming data from channel and auxiliary data on tty
* Export data to a csv file
* Adjust sample rate appropriately
* Analyze sample data with suitable tools
* Map patterns of signals to useful inputs


### Prototype Design

#### Time Requirement:

2 weeks (4 days)

#### Tasks:

* Build a daemon reading signals from tty and translate into keyboard inputs

### Product Development

#### Time Requirement:

5 weeks (10 days)

* Build an installable GUI program (.exe) showing a software keyboard and reading EEG signals from OpenBCI Dongle.

### Testing and Reporting

#### Time Requirement:

2 weeks (4 days)

#### Tasks:

* Collect more test data and generate a specific report about accuracy and precision
* ...
### division of work
* Hua Zhihao --- the project manager -- Control the whole process of project and implement the software. 
* Ma Teng --- the developer of project --- major part of Node.js server and assist the Hua Zhihao to implement the software.
* Dong Sheng -- the developer of project --- assist the Hua Zhihao to implement the software and charge the data collection and analysis
* Chu Da -- QA&DA in the project --- Do the test in the project and data collection and data analysis

Actually in the whole project we will help each other, and our role will overlap, because we only have four person and all of us want to take part in the every process of this project to learn new things.

