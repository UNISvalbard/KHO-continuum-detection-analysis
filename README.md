# KHO-continuum-detection-analysis
Software to detect and analyse auroral continuum emission in MISS and Sony all-sky camera data.

In this directory there are several python scripts. 
These scripts were written in Jupyter notebook where they can be run in parts (individual cells).

MISS-1 & MISS-2 continuum detection:
- Detect possible continuum spectra in spectral images from the MISS-1 and MISS-2 spectrograph.
- Detection is based on identifying the three main auroral emission lines and a peak in the row-wise mean.

MISS-1 & MISS-2 post-detection analysis:
- Use the output of the MISS-1 & MISS-2 continuum detection scripts.
- Noise in detected spectra is reduced and reference spectra are calculated.
- Several filtering methods are used to reduce the amount of false positives.
- MISS files are matched with Sony all-sky camera images.
- Output includes pdf files with spectral images, detected and reference spectra and Sony images.

OMNIWeb data analysis:
- Can be used to visualize and/or perform calculations on parameters downloaded from OMNIWeb data explorer.
- The matched Sony all-sky images can be used to overlay OMNIWeb data with the detected auroral events and extract the
magnitude of, for example, solar wind speeds during detected events.

Additional explanations can be found in each script.

# How to cite
If you used this code and found it advantageous for your work, consider citing it in your list of references. A recommended citation: Tim Hulsen. (2025). UNISvalbard/KHO-continuum-detection-analysis: Auroral continuum emission - detection and analysis in Python (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.15681334

You can also navigate to the publication and export the citation in different styles and formats by clicking the icon below.
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15681334.svg)](https://doi.org/10.5281/zenodo.15681334)
