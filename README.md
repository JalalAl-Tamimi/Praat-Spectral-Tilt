# Praat - Spectral Tilt

To cite, use: [![DOI](https://zenodo.org/badge/523409788.svg)](https://zenodo.org/badge/latestdoi/523409788)

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

You can also cite the following papers that used a slightly modified version of the script:
1. Al-Tamimi, J., & Khattab, G. (2018). Acoustic correlates of the voicing contrast in Lebanese Arabic singleton and geminate stops. Journal of Phonetics, Invited manuscript for the special issue of Journal of Phonetics, “Marking 50 Years of Research on Voice Onset Time and the Voicing Contrast in the World’s Languages” (eds., T. Cho, G. Docherty & D. Whalen), 71, 306–325. [https://doi.org/10.1016/j.wocn.2018.09.010](https://doi.org/10.1016/j.wocn.2018.09.010)
2. Khattab, G., Al-Tamimi, J., & Alsiraih, W. (2018). Nasalisation in the production of Iraqi Arabic pharyngeals. Phonetica, 75(4), 310–348. [https://doi.org/10.1159/000487806](https://doi.org/10.1159/000487806) 
3. Al-Tamimi, J., & Khattab, G. (2015). Acoustic cue weighting in the singleton vs geminate contrast in Lebanese Arabic: The case of fricative consonants. The Journal of the Acoustical Society of America, 138(1), 344–360. [https://doi.org/10.1121/1.4922514](https://doi.org/10.1121/1.4922514)

Cheers
