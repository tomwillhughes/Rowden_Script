# Overview
This notebook contains my solution to the Rowden Graduate Engineering - Tech Test. 
The script generates a signal composed of randomly generated sine waves combined with noise to mimic RF signals. It then transforms the signal from the time domain to the frequency domain using the Fourier transform.
# Method
Two independent filtering criteria are applied:
A) Select the three strongest frequency components (highest amplitudes)
B) Select all frequencies within a chosen frequency band
The selected frequency components are then combined and transformed back into the time domain for visualisation.
# Purpose
This project demonstrates a simple signal filtering approach. Noise and selected sine wave frequencies are extracted from the original signal.
