# Praat-Pharyngealisation

This repo contains a modified version of the Praat script used to compute the various metrics reported in Al-Tamimi (2017), including:

1. Formant frequencies 1 to 3 (in Hz), at onset and midpoint
2. Bandwidth frequencies 1 to 3 (in Hz) in addition to those obtained via the Hawks and Miller formula, at onset and midpoint
3. Intensity, at onset and midpoint
4. F0, at onset and midpoint
5. Spectral-Tilt via harmonic differences: H1*-H2*, H1*-A1*, H1*-A2*, H1*-A3*, A1*-A2*, A1*-A3*, and A2*-A3* at both onset and offset. These are the normalised versions. The non-normalised versions are available as well
6. The actual spectra saved into a new folder
7. images (in png) of the spectrogram and formants overlayed; TextGrid with segmentation, the spectrum with LPC smoothing overlayed, and the readings for all of the formants (F1, F2, F3), harmonics (H1, H2, A1, A2 and A3) and the location of the measurement. On the top of the figure, you can find readings for F1, F2 and F3 in addition to A1, A2 and A3.

Make sure to read the paper to know how these metrics were computed. It is essential to do manual checking on all of the harmonic and formant frequencies. The png images are a first step to do that, and if you need to manually correct anything, simply use the spectrum.

Get in touch in case of any difficulties!

If using this script, make sure to cite both the repo and the paper:

Al-Tamimi, J. (2017). Revisiting acoustic correlates of pharyngealization in Jordanian and Moroccan Arabic: Implications for formal representations. Laboratory
Phonology: Journal of the Association for Laboratory Phonology, 8(1), 1–40. [https://doi.org/10.5334/labphon.19](https://doi.org/10.5334/labphon.19)

Cheers
