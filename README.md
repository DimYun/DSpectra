# Read Me

This repository contains a software implementation of algorithms for X-ray spectra automatic processing. The result of the work is an "objects-properties" array of data for NPK(S) 4-30-15(16) mineral fertilizer. 

**An array contains the following properties.**
- the intensities of the characteristic lines (calculated from the smoothed spectrum and from the approximation of the lines as gauss line);
- the maximum intensity of the background line;
- area of the background line;
- type of mineral fertilizer;
- type of object (granules, pressed granules, pressed powder 500 microns and 100 microns);
- some properties of industrially produced objects (presence of preliminary drying, conditioning additive, etc.);
- conditions of measured spectrum (atmosphere, voltage, current and exposure).

**The following algorithms for processing spectra are considered.**
* Smoothing filters:
  * average;
  * median;
  * Savitsky - Golay;
  * Fourier frequency filtering.
* Baseline search:
  * Algorithm of "Zero Area".
* Search for characteristic lines:
  * differential algorithm;
  * "Zero Area" algorithm.

**Using the program.**

* The program is presented in the form of an *.ipynb file, which means that the appropriate software (jupyther notebook) and libraries for the work must be installed on the computer.
* The folder "specs.zip" contains files of X-ray spectra. Before using the program, the folder must be unpacked.
* After running the script, it's enough to run all cells sequentially to get the result.


For all questions, you can contact the author: _Dm.Yunovidov@gmail.com_




The program code is written in the Python 2.7 programming language and distributed under the Apache License
Version 2.0
