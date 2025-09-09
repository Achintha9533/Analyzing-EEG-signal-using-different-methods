# Analyzing EEG Signals for Epilepsy Diagnosis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)

# Abstract

This study investigates the use of various signal processing methods to analyze electroencephalography (EEG) signals for the diagnosis of epilepsy. The research models the brain as a system of coupled oscillators, where the reliability of the system is governed by a critical coupling strength, ϵ 
c, which is inversely proportional to the frequency distribution g(ω). By comparing different methods, the study identifies which approach is most effective for distinguishing between epileptogenic and non-epileptogenic states.

# Methodology

The research employed several signal processing techniques to analyze the EEG data:

Hilbert Transform

Empirical Mode Decomposition (EMD)

Fast Fourier Transform (FFT)

Zero Crossing Rate (ZCR)

Power Spectral Density (PSD)

Autoregressive (AR) Models

The primary focus was to analyze the relationship between the critical coupling strength (ϵ c) and the frequency distribution (g(ω)), as well as to evaluate the classification accuracy of each method in identifying epileptogenicity.

# Key Findings

A direct correlation was observed between the estimated g(ω) and the critical coupling strength ϵ c .

The FFT method demonstrated the highest frequency distribution (g(ω)=0.4898) and the lowest critical coupling strength (ϵ c = 1.3179).

The AR model had the lowest g(ω) (0.0292) and the highest ϵ c (22.0116).

For classification accuracy, the FFT method was the most reliable, with an accuracy of 59.06%.

The AR model was the least accurate, with only 32.75% accuracy.

# Note: 

The EMD and AR methods were evaluated using a reduced dataset due to high computational costs, which may have impacted their results and could potentially underestimate their true performance.

# Conclusion
The analysis demonstrates that different signal processing methods yield distinct results in the context of EEG signal analysis for epilepsy diagnosis. The Fast Fourier Transform (FFT) method proved to be the most reliable and accurate approach among those tested for this specific application.

# Author
Podimarakkala Gurunnanselage Kasun Achintha Perera
(Dated: July 20, 2025)

