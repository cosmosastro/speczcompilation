# COSMOS Spectroscopic Redshift Compilation
<!--- <i><font size="5">Collection of ~ 20 years worth of Published Spectroscopic Redshifts</font></i>
<div>
  <img src="cosmos-logo.png" alt="Image 1" style="width: 40%; display: inline-block; margin-right: 10px;">
</div>

<picture>
  <source srcset="cosmos-logo-dark.png" media="(prefers-color-scheme: dark)">
  <img src="cosmos-logo-light.png" alt="Logo">
</picture>
--->
<p align="left">
  <img src="logo/cosmos-logo-dark.png#gh-dark-mode-only" width="400">
  <img src="logo/cosmos-logo-light.png#gh-light-mode-only" width="400">
</p>

[![arXiv](https://img.shields.io/badge/arXiv-ZZZ.ZZZ-green)](ZZZ)
[![DOI](https://img.shields.io/badge/DOI-ZZZ.ZZZ-green)](ZZZ)

**Welcome to the COSMOS Spectroscopic Redshift Compilation Data Release GitHub.**



In this repository, we provide our compilation of all published redshifts within the 2 deg<sup>2</sup> COSMOS legacy field for the community to use in support of their science as well as for calibration purposes. We refer users to the main paper (LINK AS WELL) Khostovan et al. (2025) for details on how the compilation was designed. All datasets included in the compilation are astrometrically corrected to best match with GAIA DR1 (based on the COSMOS2020 Classic catalog; Weaver et al. 2022 LINK PAPER). Quality flags assigned to sources are also normalized to our specific quality assessment flag system.


The Compilation is comprised of four main files:

- specz_compilation_COSMOS_DR1.xx_all.fits
     - This encompasses all redshift measurements collected
- specz_compilation_COSMOS_DR1.xx_unique.fits
     - Filters out duplicate redshift measurements where the best redshift is assigned per source based on both recency and quality flag.
- specz_compilation_COSMOS_DR1.xx_surveys.list
     - A text file containing the numerical ID assigned to each dataset. Also included are e-mail addresses for PIs of each dataset
- specz_compilation_COSMOS_DR1.xx_surveys.pdf
     - A LaTeX longtable that shows the numerical ID of each survey as well as the paper/publication reference.


## Ancillary Measurements

### Spectral Energy Distribution (SED) Fitting

SED fitting results using both CIGALE and LePHARE can be found within `sed_fitting` folder. This was done on a subset of sources that had matches with the COSMOS2020 Classic Catalog and also were flagged as having quality flags, Q<sub>f</sub>, of 3 or 4 ('high quality/reliable'). SED fits were done using the available photometry from CFHT/*u* to *Spitzer*/IRAC with redshifts fixed to the spectroscopic redshift listed in the compilation.

Our SED-derived physical property measurements are compiled with `sed_fitting/cigale/cigale_results_specz_compilation_DR1.xx.fits` and  `sed_fitting/lephare/lephare_results_specz_compilation_DR1.xx.fits`. We plan for future data releases (including minor updates) to include update SED fitting measurements as well.

Users can also access the scripts used in the SED fitting process within the associated folders.


### Self-Organizing Maps

This is an unsupervised machine learning approach that allows for the visualization of high dimensional data sets (e.g., colors, physical properties, etc.) within a 2D grid space where objects assigned to a specific best matching unit (point in the grid space) are organized such that surrounding units have similar properties with each other (e.g., clustered groups of high mass, dusty star-forming galaxies). We train Self-Organizing Maps based on the COSMOS2020 Classic catalog thereby defining the organization of various galaxy populations photometrically available based on colors (e.g., *u - g*, *g - r*) as well as redshifts, stellar mass, and specific star formation rate (all normalized in the training process). We then project the spectroscopic redshift compilation onto the trained SOM in an effort to understand what populations currently have spectroscopic coverage and which are currently lacking. This is described in greater detail within Section 6.2 of Khostovan et al. (2025).

We provide the trained maps so that users may be able to invesigate it in respect to the compilation as well as to their own datasets (which we encourage that it be shared with the compilation if intended to be made public). Thereby, we hope that the trained soms could enable studies of populatations that have either *never been observed* or  *never extensively observed* in the past.


## Citation

We ask users to cite the following publication:
- Khostovan et al. (2025) LINK HERE

This catalog was made possible by the tremendous hard work of every person who was involved with the sample selection, mask designs, observations, data reductions, and subsequent analysis. References to each dataset are provided to give the appropriate credit and also PI/first author contact information in case there are questions regarding a specific source and/or data set.
We understand that this may not be entirely possible especially in the case where a sizable number of redshifts are used. However, we highly encourage users who use redshifts from a few programs to not only cite our main compilation paper but also all those associated with the few programs. This information can be found within ZZZ


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

Please contact Ali Ahmad Khostovan (main point-of-contact) if you have a dataset you wish to provide. The format we require are the following:\
&nbsp;&nbsp;&nbsp;*ID, RA, DEC, spectroscopic redshift, quality flag, associated publication(s)*

We also require definitions for the quality flags and may requrie further discussion to properly convert your original quality flag system to the one we adopt.



## Issues and/or Ideas?

We ask all users that have any issues with the compilation to open a ticket with the "issues" section of the github repository.

We also ask if users like to discuss ideas, potential improvements, etc. to post within the "discussions" section of the repository.



## Contact Us

Maybe I should make a single e-mail address that can be transferred?









<!---
README

Release of the TEAM ONLY spectroscopic catalog
v1.0	23 August 2023 	– Initial Release

Main Point-of-Contact: 

     Ali Ahmad Khostovan akhostov at gmail dot com

Other Contacts: 

     Jeyhan Kartaltepe	jeyhan at astro dot rit dot edu 

     Olivier Ilbert 	olivier dot ilbert at lam dot fr 

     Mara Salvato		mara at mpe dot mpg dot de

     Caitlin Casey		cmcasey at ucsb dot edu 

Citing the Compilation: 
	
     Khostovan et al., in prep

A paper is currently in the process of being written that, upon acceptance for publication, 
will make this compilation publicly available for the astronomical community to use for their 
specific science cases/goals/analyses. In the meantime, we request that the compilation is 
referred to in publications as shown above until the main paper is ready for publication.

Usage Policy:

This catalog was made possible by the tremendous hard work of every person who was involved 
with the sample selection, mask designs, observations, data reductions, and subsequent analysis. 
References to each dataset are provided to give the appropriate credit and also PI/first author 
contact information in case there are questions regarding a specific source and/or data set.

Unless communicated with the relevant PI, we ask that sources flagged as PRIVATE are not used 
for any detailed analysis of individual galaxies and only used for population level calibrations 
(e.g., checking contamination of sample, photo-z calibrations,  etc.).

We ask that this compilation stays within the COSMOS Team until it is ready for public release 
with the publication of the compilation paper.

We ask that all users of this compilation, as a courtesy, invite COSMOS collaboration PIs of 
datasets in all publications that use the corresponding spectroscopic redshifts.

# Adopted Quality Assessment Flagging System:





Associated Files:

Compilation files are listed with the prefix:
		specz_compilation_COSMOS_{MONTH}{YEAR}_v{version}

*_all.fits: All sources are included without removing duplicate sources (galaxies that have more than 1 spectroscopic redshift; e.g., observed by multiple facilities and analyzed by different groups). The first part of the list is sorted with Id_classic, then Id_Farmer, then Id_COSMOS09. Sources with the same Id_classic (etc) are duplicated. Only one of them has priority 1, keeping the source with the best quality assessment flag. Note: this catalog includes PRIVATE sources which are flagged as “public/private = 1”. Note: negative redshifts and flags are either non-detections or data sets that may need to be updated in the future (e.g., was private to us when generating the compilation).

*_unique.fits: Duplicate sources are removed from this catalog and we only keep the spectroscopic redshift that has the best flag when present in multiple surveys. 

*_public.fits: Only public spectroscopic redshifts are available in this catalog (“public/private = 0”). This also has duplicate sources removed from this catalog. Although labeled public, please do keep this catalog within the COSMOS Team until the compilation paper is published. 

list_surveys.dat: List of all surveys in the compilation with the first column being the Survey ID that is consistent with the “survey” column in the described fits files above. The second column is the name or instrument used in the survey. Third column is the publication reference. The fourth column labels if the data set is PUBLIC or TEAM ONLY (defined as private in this case). Contact information is included in the next column. The last three columns include the redshift range of the datasets (16 percentile, 50 percentile, 84 percentile).

Fits Column Definitions:

     1) Id spec-z		Assigned Unique Identification in the Compilation

     2) Id original		Original Identification of the source

     3) ra original		Original Right Ascension (deg)

     4) dec original	Original Declination (deg)

     5) ra corrected	Astrometry Corrected	Right Ascension (deg)

     6) Dec corrected	Astrometry Corrected	Declination (deg)

     7) Priority		Flag 1: Use this redshift, especially in case of duplicate sources

     8) spec-z 		Spectroscopic Redshift

     9) flag 		Quality Assessment Flag (details defined above)

     10) Confidence level	Confidence Levels associated with Quality Flag (details above)

     11) survey		Integer Value Associated with Survey ID in list_surveys.dat 

     12) compilation year	Past versions of the compilation were these sources introduced	
  
     13) public/private 	1 = PUBLIC, 0 = PRIVATE

     14) Id Classic		COSMOS2020 Classic Identification

     15) ra Classic		COSMOS2020 Classic Right Ascension (deg)

     16) dec Classic	COSMOS2020 Classic Declination (deg)

     17) Id Farmer		COSMOS2020 Farmer Identification

     18) ra Farmer		COSMOS2020 Farmer Right Ascension (deg)

     19) dec Farmer		COSMOS2020 Farmer Declination (deg)	

     20) Id COSMOS09 	COSMOS2009 i-band Identification

     21) ra COSMOS09	COSMOS2009 i-band Right Ascension (deg)

     22) dec COSMOS09	COSMOS2009 i-band Declination (deg)	

     23) photo-z 		COSMOS2020 Classic Photo-z LePhare 

     24) photo-z type	0: Galaxy; 1: star; 2: Xray source; -9: failure in fit


Compilation files are listed with the prefix:
		specz_compilation_COSMOS_{MONTH}{YEAR}_v{version}

*_all.fits: All sources are included without removing duplicate sources (galaxies that have more than 1 spectroscopic redshift; e.g., observed by multiple facilities and analyzed by different groups). The first part of the list is sorted with Id_classic, then Id_Farmer, then Id_COSMOS09. Sources with the same Id_classic (etc) are duplicated. Only one of them has priority 1, keeping the source with the best quality assessment flag. Note: this catalog includes PRIVATE sources which are flagged as “public/private = 1”. Note: negative redshifts and flags are either non-detections or data sets that may need to be updated in the future (e.g., was private to us when generating the compilation).

*_unique.fits: Duplicate sources are removed from this catalog and we only keep the spectroscopic redshift that has the best flag when present in multiple surveys. 

*_public.fits: Only public spectroscopic redshifts are available in this catalog (“public/private = 0”). This also has duplicate sources removed from this catalog. Although labeled public, please do keep this catalog within the COSMOS Team until the compilation paper is published. 

list_surveys.dat: List of all surveys in the compilation with the first column being the Survey ID that is consistent with the “survey” column in the described fits files above. The second column is the name or instrument used in the survey. Third column is the publication reference. The fourth column labels if the data set is PUBLIC or TEAM ONLY (defined as private in this case). Contact information is included in the next column. The last three columns include the redshift range of the datasets (16 percentile, 50 percentile, 84 percentile).
--->