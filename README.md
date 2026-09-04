#ELEC5305 Project: Automatic Segmentation and Structural Analysis of Humpback Whale Song

## Overview
This project investigates humpback whale song, which is organised hierarchically into
units, phrases, and themes. The goal is to build a MATLAB-based signal-processing
pipeline that automatically segments whale song recordings into their component units
and phrases, and discovers recurring phrase patterns — without relying on hand-labelled
training data.

## Approach
- Band-pass filtering and normalisation of raw hydrophone recordings
- Short-time Fourier transform (STFT) for time-frequency analysis
- Energy-based onset/offset detection to segment individual sound units
- Feature extraction (MFCCs, spectral centroid, duration)
- Clustering and sequence analysis to identify recurring phrases/themes
- Evaluation against existing annotated song transcriptions

## Data
- [ocean mammal Institute](http://www.oceanmammalinst.org/songs.html)
  

## Tools
MATLAB (Signal Processing Toolbox, Audio Toolbox)

## Author
Sabrina Cai — ELEC5305, University of Sydney

## Proposal
See [ELEC5305_Project_Proposal.pdf](./ELEC5305_Project_Proposal.pdf) for the full project proposal.
