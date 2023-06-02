# EEG-Stress-Detection

This repository contains the code and documentation for a Brain-Computer Interface (BCI) project aimed at improving the lives of individuals experiencing daily stress. The project utilizes cutting-edge technology to detect stress by analyzing alpha and beta activities in the frontal lobe and monitoring brain activity in the frontal lobe.

## 1. Data Collection: 
The project involved placing 8 EEG electrodes on specific positions on the subject's head to read neural signals. The OpenBCI hardware and software were used to record the raw data.

## 2. Preprocessing: 
The collected neural data underwent preprocessing steps to filter out noise and artifacts. This involved applying a band-pass filter to retain alpha and beta wave frequencies, applying IIR and FIR filters to enhance the signal of interest, and using a notch filter to remove power grid interference.

## 3. Real-Time Implementation: 
The BCI system was implemented for real-time usage using a threshold system. EEG data collected from subjects is streamed in real time, preprocessed, and analyzed for a spike in the beta band frequency. If stress-related EEG activity is detected, a curated Spotify playlist containing calming music is played until the classifier no longer detects stress.

## 4. Evaluation and Results: 
The repository includes code to evaluate the effectiveness of stress detection and the impact of calming music. The project aims to accurately differentiate stress-indicating data and observe the reduction of stress through music therapy.

## Vision:
The aim of this project is to reduce stress levels, improve productivity, and enhance overall well-being. By providing a BCI-based approach to stress management, this repository contributes to the field of stress research and offers potential interventions for stress reduction.
