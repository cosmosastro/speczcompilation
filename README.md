# COSMOS Spectroscopic Redshift Compilation
<p align="left">
  <img src="logo/cosmos-logo-dark.png#gh-dark-mode-only" width="400">
  <img src="logo/cosmos-logo-light.png#gh-light-mode-only" width="400">
</p>

[![arXiv](https://img.shields.io/badge/arXiv-ZZZ.ZZZ-green)](ZZZ)
[![DOI](https://img.shields.io/badge/DOI-ZZZ.ZZZ-green)](ZZZ)

**Welcome to the COSMOS Spectroscopic Redshift Compilation Data Release GitHub.**



In this repository, we provide our compilation of all published redshifts within the 2 deg<sup>2</sup> COSMOS legacy field for the community to use in support of their science as well as for calibration purposes. We refer users to the main paper [Khostovan et al. (2025)](ZZZ) for details on how the compilation was designed. All datasets included in the compilation are astrometrically corrected to best match with GAIA DR1 (based on the COSMOS2020 Classic catalog; [Weaver et al. 2022](https://ui.adsabs.harvard.edu/abs/2022ApJS..258...11W/abstract)). Quality flags assigned to sources are also normalized to our specific quality assessment flag system.


The Compilation is comprised of four main files:

- `specz_compilation_COSMOS_DR1.xx_all.fits`
     - This encompasses all redshift measurements collected
- `specz_compilation_COSMOS_DR1.xx_unique.fits`
     - Filters out duplicate redshift measurements where the best redshift is assigned per source based on both recency and quality flag.
- `specz_compilation_COSMOS_DR1.xx_surveys.list`
     - A text file containing the numerical ID assigned to each dataset. Also included are e-mail addresses for PIs of each dataset

## Ancillary Measurements

### Spectral Energy Distribution (SED) Fitting

SED fitting results using both CIGALE and LePHARE can be found within `sed_fitting` folder. This was done on a subset of sources that had matches with the COSMOS2020 Classic catalog and also were flagged as having quality flags, Q<sub>f</sub>, of 3 or 4 ('high quality/reliable'). SED fits were done using the available photometry from CFHT/*u* to *Spitzer*/IRAC with redshifts fixed to the spectroscopic redshift listed in the compilation.

Our SED-derived physical property measurements are compiled within `sed_fitting/cigale/cigale_results_specz_compilation_DR1.xx.fits` and  `sed_fitting/lephare/lephare_results_specz_compilation_DR1.xx.fits`. We plan for future data releases (including minor updates) to include update SED fitting measurements as well.

Users can also access the scripts used in the SED fitting process within the associated folders.


<span style="color:red">*WARNING:* </span> Although we removed sources flagged as BL-AGN from the subset used in the SED fitting process, we note that not all programs explicitly identified BL-AGN. Furthermore, X-ray and IR AGN are not removed from this subset. Therefore, we urge caution to users who use the SED results for sources that are AGN and recommend to reasess SED fitting using the appropriate AGN-based templates and models.



### Self-Organizing Maps

This is an unsupervised machine learning approach that allows for the visualization of high dimensional data sets (e.g., colors, physical properties, etc.) within a 2D grid space where objects assigned to a specific best matching unit (point in the grid space) are organized such that surrounding units have similar properties with each other (e.g., clustered groups of high mass, dusty star-forming galaxies). We train Self-Organizing Maps based on the COSMOS2020 Classic catalog thereby defining the organization of various galaxy populations photometrically available based on colors (e.g., *u - g*, *g - r*) as well as redshifts, stellar mass, and specific star formation rate (all normalized in the training process). We then project the spectroscopic redshift compilation onto the trained SOM in an effort to understand what populations currently have spectroscopic coverage and which are currently lacking. This is described in greater detail within Section 6.2 of Khostovan et al. (2025).

We provide the trained maps so that users may be able to invesigate it in respect to the compilation as well as to their own datasets (which we encourage that it be shared with the compilation if intended to be made public). Thereby, we hope that the trained soms could enable studies of populatations that have either *never been observed* or  *never extensively observed* in the past.


## Citation

We ask users to cite the following publication:
- [Khostovan et al. (2025), submitted to ApJ](ZZZ); [arXiv:ZZZ](ZZZ)

This catalog was made possible by the tremendous hard work of every person who was involved with the sample selection, mask designs, observations, data reductions, and subsequent analysis. References to each dataset are provided to give the appropriate credit and also PI/first author contact information in case there are questions regarding a specific source and/or data set.
We understand that this may not be entirely possible especially in the case where a sizable number of redshifts are used. However, we highly encourage users who use redshifts from a few programs to not only cite our main compilation paper but also all those associated with the few programs. This information can be found within the README of the `specz_compilation` folder.


## Quality Assessment Flagging System

The quality assessment flag system that we adopt is based on a 0 - 4, 9 scale with an additional +10 for the case of broad line features identified within the 1D and 2D spectra.

| Quality Flag | Confidence Level (%) | Description |
| ------------ | ---------------- |  ---------- | 
|      4       | 97  | Very Reliable Redshift |
|      3       | 95  | Reliable Redshift |
|      2       | 80  | Moderate Detection of Emission Lines |
|      1       | 50  | Tentative Measurement | 
|      0       |  -   | No Measurement |
|      9       | 85   | Single Line Detection with Good S/N |
|    +10       | -    | Broad Line Feature (e.g., BL-AGN) |

In forming the compilation, each original dataset that is included has the original quality flag assigned converted to conform to our system. We provide further detail in Section 3.1 of Khostovan et al. (2025) on how this conversion is done, especially for programs such as DESI-EDR that adopted a completely different quality flagging system compared to traditional approaches (e.g., integer-based, inclusion of decimal factors for further classification/quality definitions).



## Have a Dataset you want to add?

The COSMOS Spectroscopic Redshift Compilation is meant to be a lasting and continuously evolving legacy resource for the community encompassing the tremendous amount of spectroscopic data and the hardwork of all those involved in proposal writing, observations, data gathering, reduction, and analysis. As such, we highly recommend for all members of the community to send us any past and new spectroscopic redshift datasets that are currently not included in the compilation. We will periodically investigate catalog archives, publications, survey websites, and various other resources for new data that comes in. However, with your support, we can append data that we potentially miss in our own search into this single large, ever evolving, legacy resource.

Please contact `cosmosleadership [at] gmail [dot] com` if you have a dataset you wish to provide. The format we require are the following:\
&nbsp;&nbsp;&nbsp;*ID, RA, DEC, spectroscopic redshift, quality flag, associated publication(s)*

We also require definitions for the quality flags and may requrie further discussion to properly convert your original quality flag system to the one we adopt.



## Issues and/or Ideas?

We ask all users that have any issues with the compilation to open a ticket with the "issues" section of the github repository.

We also ask if users like to discuss ideas, potential improvements, etc. to post within the "discussions" section of the repository.



## Contact Us

Feel free to reach us at `cosmosleadership [at] gmail [dot] com`

Ali Ahmad Khostovan (main point-of-contact) <br>
Jeyhan Kartaltepe <br>	
Olivier Ilbert  <br>	
Mara Salvato	 <br>	
Caitlin Casey		
