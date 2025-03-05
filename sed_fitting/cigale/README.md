## CIGALE SED Fitting Results

The CIGALE results FITS file has many columns which are general outputs for which we refer the user to their [documentation](https://gitlab.lam.fr/cigale/manual) for further details. Here we highlight several key parameters included in the FITS file. Note that `best.[property]` corresponds to the measurement associated with the best-fit CIGALE template (minimum &chi;<sup>2</sup>). We also implement CIGALE's bayesian-like analysis calculates the marginalized probability distribution functions (PDFs) associated with the likelihood measurements of each CIGALE model used in the SED fitting process. Properties that are measured using this Bayesian analysis are labeled as `bayes.[property]` and `bayes.[property]_err` representing the probability-weighted mean and standard deviation of the PDF.

|   Property         |    best   |  bayes   |   Unit                  |       Description                              |
| ----------------   | --------- | -------- |------------------------ | ---------------------------------------------- |
| ID_COS20_Classic   |           |          |                         | COSMOS2020 Classic ID |             
| specz              |           |          |                         | Spectroscopic Redshift                |                    
| chi_square         |  &check;  | &cross;  |                         | &chi;<sup>2</sup> of the Fit |
| reduced_chi_square |  &check;  | &cross;  |                         | reduced &chi;<sup>2</sup> of the Fit |  
| attenuation.E_BV_lines |   &check;  | &check;  |  mag     | Reddening (nebular-stellar reddening factor is 1) |
| nebular.logU |    &check;  | &cross;  |             | Ionization Parameter log<sub>10</sub> *U* |
| nebular.zgas |    &check;  | &cross;  |             | Gas-phase Metallicity     |
| param.D_4000 |    &check;  | &check;  |             | Modeled 4000&#8491; index |
| param.EW(*&lambda;/1.0*) |  &check;  | &check;  | nm  | Modeled Rest-Frame Equivalent Width of emission line at central &lambda; calculated in a window of size 1.0 nm |
| line.*name* |      &check;  | &check;  | W m<sup>-2</sup> | Modeled Emission Line Flux |
| param.beta0_calz94 |    &check;  | &check;  |         | Intrinsic UV Spectral Slope  |
| param.beta_calz94 |     &check;  | &check;  |         | Observed UV Spectral Slope |
| param.restframe_NUV-SUBARU_r |     &check;  | &check;  | mag   |   Rest-frame *(NUV - r)* color |
| param.restframe_SUBARU_U-SUBARU_V |     &check;  | &check;  | mag   |   Rest-frame *(U - V)* color | 
| param.restframe_SUBARU_V-vista.vircam.J |     &check;  | &check;  |  mag   |   Rest-frame *V - J* color |
| param.restframe_SUBARU_r-vista.vircam.J |     &check;  | &check;  |  mag   |   Rest-frame *r - J* color |
| sfh.age |      &check;  | &cross;  | Myr | Age of the oldest stars in the galaxy |
| sfh.age_burst |      &check;  | &check;  | Myr | Age of the late burst |
| sfh.age_main |     &check;  | &check;  |   Myr | Age of the main population |
| sfh.f_burst |     &check;  | &check;  |        | Mass fraction of the late burst population |
| sfh.tau_burst |     &check;  | &check;  | Myr  | *e*-folding time of the late starburst population |
| sfh.tau_main |     &check;  | &check;  |  Myr  | *e*-folding time of the main stellar population |
| stellar.age_m_star |     &check;  | &cross;  | Myr | Mass-weighted age of the stellar population | 
| stellar.metallicity |      &check;  | &check;  |   | Stellar Metallicity |
| param.restframe_Lnu(TopHat_1500_100) |      &check;  | &check;  | W Hz<sup>-1</sup> | Rest-frame 1500&#8491; Luminosity (*L<sub>&nu;</sub>*) measured in a TopHat Filter with width of 100&#8491; |
| param.restframe_Lnu(*filter*) |      &check;  | &cross;  | W Hz<sup>-1</sup>  | Rest-frame *L<sub>&nu;</sub>* luminosity in a given filter |
| sfh.sfr |      &check;  | &check;  |  M<sub>☉</sub> yr<sup>-1</sup> | Instantaneous Star Formation Rate |
| sfh.sfr100Myrs |      &check;  | &check;  | M<sub>☉</sub> yr<sup>-1</sup> | Star Formation Rate within 10 Myrs |
| sfh.sfr10Myrs |      &check;  | &check;  | M<sub>☉</sub> yr<sup>-1</sup> | Star Formation Rate within 100 Myrs |
| stellar.m_gas |      &check;  | &check;  | M<sub>☉</sub> | Gas Mass |
| stellar.m_star |      &check;  | &check;  |  M<sub>☉</sub> | Stellar Mass |
| stellar.n_ly |      &check;  | &check;  |  photons s<sup>-1</sup> | Number of Hydrogen Ionizing Photons Produced |

Photometry included in the FITS file correspond to the following:
- if named `best.[filter_name]` or `bayes.[filter_name]` &rarr; modeled photometry from CIGALE
- if simply named `[filter_name]` and `[filter_name]_err` &rarr; observed photometry and errors from COSMOS2020/Classic Catalog used in the CIGALE SED fitting
- All units are in mJy


