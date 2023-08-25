# speczcompilation

README

Release of the TEAM ONLY spectroscopic catalog
v1.0	23 August 2023 	– Initial Release

Main Contact: 

Ali Ahmad Khostovan akhostov@gmail.com

Other Contacts: 

Jeyhan Kartaltepe	jeyhan@astro.rit.edu 
Olivier Ilbert 		olivier.ilbert@lam.fr 
Mara Salvato		mara@mpe.mpg.de
Caitlin Casey		cmcasey@utexas.edu 

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

Adopted Quality Assessment Flagging System:

Flag 4 very reliable redshift (confidence level >97%)
Flag 3 reliable redshift (confidence level > 95%)
Flag 9 single line only, with a good S/N, but nothing else (confidence level  > 85%)
Flag 2 intermediate (confidence level >80%)
Flag 1 tentative measurement (confidence level >50%)
Flag 0 No measurement
Flag + 10 indicated broad line feature

Associated Files:

Compilation files are listed with the prefix:
		specz_compilation_COSMOS_{MONTH}{YEAR}_v{version}

*_all.fits: All sources are included without removing duplicate sources (galaxies that have more than 1 spectroscopic redshift; e.g., observed by multiple facilities and analyzed by different groups). The first part of the list is sorted with Id_classic, then Id_Farmer, then Id_COSMOS09. Sources with the same Id_classic (etc) are duplicated. Only one of them has priority 1, keeping the source with the best quality assessment flag. Note: this catalog includes PRIVATE sources which are flagged as “public/private = 1”. Note: negative redshifts and flags are either non-detections or data sets that may need to be updated in the future (e.g., was private to us when generating the compilation).

*_unique.fits: Duplicate sources are removed from this catalog and we only keep the spectroscopic redshift that has the best flag when present in multiple surveys. 

*_public.fits: Only public spectroscopic redshifts are available in this catalog (“public/private = 0”). This also has duplicate sources removed from this catalog. Although labeled public, please do keep this catalog within the COSMOS Team until the compilation paper is published. 

list_surveys.dat: List of all surveys in the compilation with the first column being the Survey ID that is consistent with the “survey” column in the described fits files above. The second column is the name or instrument used in the survey. Third column is the publication reference. The fourth column labels if the data set is PUBLIC or TEAM ONLY (defined as private in this case). Contact information is included in the next column. The last three columns include the redshift range of the datasets (16 percentile, 50 percentile, 84 percentile).

Fits Column Definitions:

Id spec-z		Assigned Unique Identification in the Compilation
Id original		Original Identification of the source
ra original		Original Right Ascension (deg)
dec original		Original Declination (deg)
ra corrected		Astrometry Corrected	Right Ascension (deg)
Dec corrected		Astrometry Corrected	Declination (deg)
Priority		Flag 1: Use this redshift, especially in case of duplicate sources
spec-z 			Spectroscopic Redshift
flag 			Quality Assessment Flag (details defined above)
Confidence level	Confidence Levels associated with Quality Flag (details above)
survey			Integer Value Associated with Survey ID in list_surveys.dat 
compilation year	Past versions of the compilation were these sources introduced	
public/private 		1 = PUBLIC, 0 = PRIVATE
Id Classic		COSMOS2020 Classic Identification
ra Classic		COSMOS2020 Classic Right Ascension (deg)
dec Classic		COSMOS2020 Classic Declination (deg)
Id Farmer		COSMOS2020 Farmer Identification
ra Farmer		COSMOS2020 Farmer Right Ascension (deg)
dec Farmer		COSMOS2020 Farmer Declination (deg)	
Id COSMOS09 	COSMOS2009 i-band Identification
ra COSMOS09	COSMOS2009 i-band Right Ascension (deg)
dec COSMOS09	COSMOS2009 i-band Declination (deg)	
photo-z 		COSMOS2020 Classic Photo-z LePhare 
photo-z type		0: Galaxy; 1: star; 2: Xray source; -9: failure in fit
