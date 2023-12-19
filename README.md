# Audio2Speech

## Overview

This Python project leverages state-of-the-art techniques to learn audio samples and predict common commands (up, down, right, left). The audios were converted to log-mel spectrograms. 

## Procedure
- Log-mel spectrograms were created for various audio tracks
  
 <img src="https://github.com/sanjeet178/Audio2Speech/assets/69724036/8b648d0b-aee3-4cc1-9834-99dbe614c924" width="400">

- Data Augmentation techniques were implmented on spectrograms
- CNN (convolutional neural network) was trained was classifying the sounds
  
## Augmentation Techniques implemented
- VLTP (Vocal-Tract Length Perturbation), Time stretching, Volume standardisation
Several Augmentation techniques were tried and tested, it was found that the aforementioned augmentation techniques were the most robust in terms of performance and output.

## Results
- Accuracy:-0.8

## References
- https://pdfs.semanticscholar.org/3de0/616eb3cd4554fdf9fd65c9c82f2605a17413.pdf
- https://link.springer.com/content/pdf/10.1186/s13636-015-0068-3.pdf
- https://towardsdatascience.com/getting-to-know-the-mel-spectrogram-31bca3e2d9d0
