# EEG-Stress-Detection

This repository contains the code and documentation for a Brain-Computer Interface (BCI) project aimed at improving the lives of individuals experiencing daily stress. The project utilizes cutting-edge technology to detect stress by analyzing alpha and beta activities in the frontal lobe and monitoring brain activity in the frontal lobe.

## Aim:

The repository aims to provide an open-source solution for stress detection using EEG signals and its subsequent management through music therapy. The code, documentation, and results included in the repository enable researchers and developers to understand and contribute to the ongoing efforts in stress reduction and mental health improvement.

## 1. Data Collection: 

The project involved placing 8 EEG electrodes on specific positions on the subject's head to read neural signals. The OpenBCI hardware and software were used to record the raw data.

## 2. Preprocessing: 

The collected neural data underwent preprocessing steps to filter out noise and artifacts. This involved applying a band-pass filter to retain alpha and beta wave frequencies, applying IIR and FIR filters to enhance the signal of interest, and using a notch filter to remove power grid interference.

## 3. Real-Time Implementation: 

The BCI system was implemented for real-time usage using a threshold system. EEG data collected from subjects is streamed in real time, preprocessed, and analyzed for a spike in the beta band frequency. If stress-related EEG activity is detected, a curated Spotify playlist containing calming music is played until the classifier no longer detects stress.

## 4. Evaluation and Results: 
The repository includes code to evaluate the effectiveness of stress detection and the impact of calming music. The project aims to accurately differentiate stress-indicating data and observe the reduction of stress through music therapy.

## Vision:

The future vision for this technology is to empower individuals to monitor and regulate their own stress levels in real-time, enabling timely intervention and improved stress management. One potential application of this technology is in the academic setting, where it could play a crucial role in alleviating academic stress. By analyzing the individual's stress levels through EEG signals, the system can select and play music that improves mood and promotes relaxation specifically tailored to students engaging in academic tasks. 

It is important to address the limitations of the current study, such as the small sample size and limited data collected. In the future, there are plans to collect data from a larger and more diverse set of participants, enabling the development of a more robust and accurate stress detection and music therapy model. By expanding the dataset, researchers can improve the reliability and generalizability of the technology, making it more effective for a wider range of individuals.

