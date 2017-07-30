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
* Test EMG and EEG activities against OpenBCI GUI


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
* ...


### Product Development

#### Time Requirement:

4 weeks (8 days)

* Build a GUI program showing a software keyboard and accepting keyboard inputs from daemon
* ...


### Testing and Reporting

#### Time Requirement:

2 weeks (4 days)

#### Tasks:

* Collect more test data and generate a specific report about accuracy and precision
* ...
