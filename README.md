Analyzing EEG Signals for Epilepsy Diagnosis
Abstract
This study investigates the use of various signal processing methods to analyze electroencephalography (EEG) signals for the diagnosis of epilepsy. The research models the brain as a system of coupled oscillators, where the reliability of the system is governed by a critical coupling strength, 
epsilon_c, which is inversely proportional to the frequency distribution g(
omega). By comparing different methods, the study identifies which approach is most effective for distinguishing between epileptogenic and non-epileptogenic states.

Methodology
The research employed several signal processing techniques to analyze the EEG data. The primary focus was to analyze the relationship between the critical coupling strength (
epsilon_c) and the frequency distribution (g(
omega)), as well as to evaluate the classification accuracy of each method in identifying epileptogenicity.

The following methods were used:

Hilbert Transform

Empirical Mode Decomposition (EMD)

Fast Fourier Transform (FFT)

Zero Crossing Rate (ZCR)

Power Spectral Density (PSD)

Autoregressive (AR) Models

Key Findings
A direct correlation was observed between the estimated g(
omega) and the critical coupling strength 
epsilon_c.

Method

Frequency Distribution (g(
omega))

Critical Coupling Strength (
epsilon_c)

Classification Accuracy

FFT

0.4898

1.3179

59.06%

AR

0.0292

22.0116

32.75%

The FFT method demonstrated the highest frequency distribution and the lowest critical coupling strength.

The AR model had the lowest g(
omega) and the highest 
epsilon_c.

For classification accuracy, the FFT method was the most reliable, while the AR model was the least accurate.

Note: The EMD and AR methods were evaluated using a reduced dataset due to high computational costs, which may have impacted their results and could potentially underestimate their true performance.

Conclusion
The analysis demonstrates that different signal processing methods yield distinct results in the context of EEG signal analysis for epilepsy diagnosis. The Fast Fourier Transform (FFT) method proved to be the most reliable and accurate approach among those tested for this specific application.

Author
Name: Podimarakkala Gurunnanselage Kasun Achintha Perera

Date: July 20, 2025