## List of Surveys Included in the Compilation

The compilation consists of three key files: 
-   `_all.fits`: corresponds to all redshift measurements
-   `_unique.fits`: corresponds to all unique sources with those having duplicate redshift measurements having their best spectroscopic redshift assigned based on the highest quality flag. In the case where a source has 2 redshifts of equal quality flag, we assign the most recent redshift as the 'best' spectroscopic redshift
-   `_surveys.list`: an ASCII file that contains the survey ID number assigned in the FITS files under the column `survey', the survey name, a simple reference placeholder, status of the survey, contact information for PI, number of galaxies in the survey, and key statistics on the redshift distribution.

For convenience, we outline the survey information within DR1.1 with links to their respective publications. In the case only a portion of the compilation is used, we highly encourage users (if possible) to cite the references associated with the programs for which the redshifts are drawn from in addition to our compilation publication.

<div style="overflow-x:auto; font-size: 12px;">

| Survey ID  | Survey Name    | Telescope/Instrument        | Type                | Redshift Range  | # of Galaxies | Reference(s) or PI |
| -----------| -------------- |  ---------------------      | ---------------     | --------------- |  ------------ |  ---------------   |  
|   1        | 2dFGRS         | AAT/2dF                     | (G) Opt             | 0.00 -- 0.33    |  222          | [Colless et al. (2001)](https://ui.adsabs.harvard.edu/abs/2001MNRAS.328.1039C/abstract) |
|   2        | 3DHST          | *HST*/WFC3 & *HST*/ACS      | (S) Opt+NIR         | 0.00 -- 1.34    |  455          | [Brammer et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJS..200...13B/abstract), [Momcheva et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJS..225...27M/abstract) |
|   3        |   --           | AAT                         | (G) Opt             | 0.00 -- 3.29    |  636          | Suzuki et al., (*in prep*) |
|   4        |   --           | ALMA                        | (G) submm/mm        | 4.32 -- 4.33    |  2            | [Brinch et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025A%26A...694A.218B/abstract) |
|   5        |   --           | ALMA                        | (G) submm/mm        | 2.49 -- 2.51    |  7            | [Champagne et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021ApJ...913..110C/abstract) |
|   6        |   --           | ALMA                        | (G) submm/mm        | 2.78 -- 4.75    |  9            | [Gentile et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...687A.288G/abstract) |
|   7        |   --           | ALMA                        | (G) submm/mm        | 3.62 -- 5.85    |  4            | [Jin et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...887..144J/abstract) |
|   8        |   --           | ALMA                        | (G) submm/mm        | 2.625           |  1            | [Jin et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...690L..16J/abstract) |
|   9        |   --           | ALMA                        | (G) submm/mm        | 6.75 -- 7.06    |  3            | [Schouws et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...954..103S/abstract) |
|  10        |   --           | ALMA                        | (G) submm/mm        | 3.71 -- 3.72    |  2            | [Schreiber et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018A%26A...611A..22S/abstract) |
|  11        |   --           | ALMA                        | (G) submm/mm        | 4.820           |  1            | [Sillassen et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025A%26A...693A.309S/abstract) |
|  12        |   --           | ALMA                        | (G) submm/mm        | 6.81 -- 6.85    |  2            | [Smit et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018Natur.553..178S/abstract) |
|  13        |   --           | ALMA                        | (G) submm/mm        | 1.15 -- 1.63    |  55           | [Valentino et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJ...869...27V/abstract), [2020a](https://ui.adsabs.harvard.edu/abs/2020ApJ...890...24V/abstract), [2020b](https://ui.adsabs.harvard.edu/abs/2020A%26A...641A.155V/abstract) |
|  14        | AS2COSPEC      | ALMA                        | (G) submm/mm        | 1.90 -- 4.78    |  18           | [Chen et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...931..160B/abstract) |
|  15        | AzTEC COSMOS   | LMT/RSR & SMA/SIS           | (G) submm/mm        | 4.34            |  1            | [Yun et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015MNRAS.454.3485Y/abstract) |
|  16        | AzTEC COSMOS   | ALMA & NOEMA                | (G) submm/mm        | 4.63            |  2            | [Jimenez et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...890..171J/abstract) |
|  17        | BRiZELS	      | WHT/LIRIS \& TNG/NICS       | (G) NIR             | 0.84 -- 2.28    |  17           | [Sobral et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.457.1739S/abstract) |
|  18        | C3R2-DR3       | Keck/LRIS, DEIMOS, MOSFIRE  | (G) Opt+NIR         | 0.10 -- 4.17    |  347          | [Stanford et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021ApJS..256....9S/abstract) |
|  19        | C3R2-LBT       | LBT/LUCI1, LUCI2            | (G) NIR             | 1.32 -- 2.56    |  163          | [Saglia et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022A%26A...664A.196E/abstract) |
|  20        | C3R2           | Keck/LRIS, DEIMOS, MOSFIRE  | (G) Opt+NIR         | 0.00 -- 4.50    |  2869         | [Masters et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...841..111M/abstract), [2019](https://ui.adsabs.harvard.edu/abs/2019ApJ...877...81M/abstract) |
|  21        | CANDELSz7      | VLT/FORS2                   | (G) Opt             | 0.66 -- 7.14    |  18           | [Pentericci et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018A%26A...619A.147P/abstract) |
|  22        | CAPERS         | *JWST*/NIRSpec              | (S) NIR             | 9.288           |  1            | [Taylor et al. (2025b)](https://ui.adsabs.harvard.edu/abs/2025ApJ...989L...7T/abstract) |
|  23        | CHESS          | Keck/DEIMOS                 | (G) Opt             | 0.08 -- 1.61    |  233          | Lertprasertpong et al., (*in prep*) |
|  24        | CHILES         | ALMA                        | (G) submm/mm        | 0.01 -- 1.29    |  80           | Blue Bird et al., (*in prep*) |
|  25        | CLAMATO DR2    | Keck/LRIS                   | (G) Opt             | 0.05 -- 3.52    |  600          | [Lee et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJS..237...31L/abstract), [Horowitz et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJS..263...27H/abstract) |
|  26        | --             | MMT/Binospec                | (G) Opt             | 6.70 -- 6.88    |  9            | [Endsley et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022MNRAS.511.6042E/abstract) | 
|  27        | --             | VLT/XSHOOTER, Keck/DEIMOS   | (G) Opt             | 6.54 -- 6.60    |  2            | [Sobral et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...808..139S/abstract) | 
|  28        | --             | Keck/DEIMOS                 | (G) Opt             | 0.37 -- 6.32    |  22           | [Brinch et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024MNRAS.527.6591B/abstract)  |
|  29        | --             | Keck/DEIMOS                 | (G) Opt             | 0.03 -- 6.47    |  3158         | PI: Peter Capak |
|  30        | --             | Keck/DEIMOS                 | (G) Opt             | 0.12 -- 1.52    |  156          | [Casey et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJ...761..140C/abstract) |
|  31        | 10K-DEIMOS     | Keck/DEIMOS                 | (G) Opt             | 0.00 -- 6.60    |  10718        | [Hasinger et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJ...858...77H/abstract) |
|  32        | --             | Keck/DEIMOS                 | (G) Opt             | 5.67 -- 5.75    |  6            | [Henry et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJ...744..149H/abstract) |
|  33        | --             | Keck/DEIMOS                 | (G) Opt             | 0.00 -- 5.04    |  1059         | [Kartaltepe et al. (2010)](https://ui.adsabs.harvard.edu/abs/2010ApJ...709..572K/abstract) |
|  34        | --             | Keck/DEIMOS                 | (G) Opt             | 0.39 -- 5.01    |  143          | PI: Mara Salvato |
|  35        | --             | Keck/DEIMOS                 | (G) Opt             | 0.08 -- 1.76    |  225          | [Shah et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...904..107S/abstract) |
|  36        | --             | Keck/DEIMOS                 | (G) Opt             | 6.54 -- 6.60    |  3            | [Taylor et al. (2025a)](https://ui.adsabs.harvard.edu/abs/2025ApJ...989...31T/abstract) |
|  37        | DESI-DR1       | Mayall/DESI                 | (G) Opt             | 0.00 -- 6.81    |  96255        | [DESI Collaboration et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025arXiv250314745D/abstract) |
|  38        | DESI-DR2       | Mayall/DESI                 | (G) Opt             | 0.00 -- 6.65    |  201445       | [Ratajczak et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025arXiv250809286R/abstract) |
|  39        | DESI-EDR       | Mayall/DESI                 | (G) Opt             | 0.00 -- 5.81    |  55327        | [Adame et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024AJ....168...58D/abstract) |
|  40        | FENIKS         | Keck/MOSFIRE                | (G) NIR             | 3.34 -- 4.67    |  4            | [Antwi-Danso et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025ApJ...978...90A/abstract) |
|  41        | FMOS--COSMOS   | Subaru/FMOS                 | (G) NIR             | 0.37 -- 4.64    |  988          | [Kartaltepe et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...806L..35K/abstract) | 
|  42        | FMOS--COSMOS   | Subaru/FMOS                 | (G) NIR             | 0.70 -- 2.59    |  5484         | [Kashino et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJS..241...10K/abstract) |
|  43        | --             | Subaru/FMOS                 | (G) NIR             | 0.60 -- 1.45    |  539          | PI: Tohru Nagao |
|  44        | --             | Subaru/FMOS                 | (G) NIR             | 0.68 -- 1.57    |  85           | [Roseboom et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012MNRAS.426.1782R/abstract) |
|  45        | --             | Subaru/FOCAS                | (G) Opt             | 0.05 -- 3.88    |  114          | PI: Tohru Nagao |
|  46        | --             | Subaru/FOCAS                | (G) Opt             | 0.828           |  1            | [Zhu et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025ApJ...982...27Z/abstract) |
|  47        | --             | VLT/FORS2                   | (G) Opt             | 0.08 -- 5.49    |  1767         | [Comparat et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015A%26A...575A..40C/abstract) |
|  48        | --             | VLT/FORS2                   | (G) Opt             | 2.44 -- 2.45    |  11           | [Diener et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...802...31D/abstract) |
|  49        | --             | VLT/FORS2                   | (G) Opt             | 0.04 -- 1.29    |  530          | [George et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011ApJ...742..125G/abstract) |
|  50        | --             | VLT/FORS1                   | (G) Opt             | 0.03 -- 1.15    |  54           | [Faure et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011A%26A...529A..72F/abstract) |      
|  51        | GEEC2          | Gemini-S/GMOS               | (G) Opt             | 0.12 -- 1.51    |  807          | [Balogh et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011MNRAS.412.2303B/abstract) |
|  52        | --             | Gemini-S/GMOS               | (G) Opt             | 0.10 -- 1.66    |  124          | Cox et al. (*in prep*) |
|  53        | --             | Gemini-S/GMOS               | (G) Opt             | 0.8275          |  1            | [Khostovan et al. (2025)](https://ui.adsabs.harvard.edu/abs/2024arXiv241110537K/abstract) |
|  54        | GOGREEN-DR1    | Gemini/GMOS                 | (G) Opt             | 0.50 -- 2.32    |  226          | [Balogh et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021MNRAS.500..358B/abstract) |
|  55        | HALO7D         | Keck/DEIMOS                 | (G) Opt             | 0.29 -- 1.52    |  533          | [Pharo et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJS..261...12P/abstract) |
|  56        | --             | MMT/Hectospec               | (G) Opt             | 0.00 -- 1.44    |  277          | [Sohn et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...880..142S/abstract) |
|  57        | HETDEX-DR2     | HET/VIRUS                   | (G) Opt             | 0.01 -- 3.51    |  2447         | [Mentuch Cooper et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...943..177M/abstract) |
|  58        | HETVIPS        | HET/VIRUS                   | (G) Opt             | 0.00 -- 2.10    |  325          | [Zeimann et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...966...14Z/abstract) |
|  59        | HMS            | Keck/LRIS, MOSFIRE          | (G) Opt+NIR         | 1.36 -- 2.24    |  21           | [Kriek et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...966...36K/abstract) |
|  60        | HR-COSMOS      | VLT/VIMOS                   | (G) Opt+NIR         | 0.74 -- 1.18    |  82           | [Pelliccia et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017A%26A...599A..25P/abstract) | 
|  61        | *HST*-Hyperion | *HST*/WFC3                  | (S) Opt+NIR         | 0.00 -- 5.99    |  12814        | [Forrest et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025ApJ...985...61F/abstract) |
|  62        | --             | Magellan/IMACS              | (G) Opt             | 0.00 -- 4.66    |  2858         | [Trump et al. (2007)](https://ui.adsabs.harvard.edu/abs/2007ApJS..172..383T/abstract) |
|  63        | --             | \it{Spitzer}/IRS            | (S) MIR             | 0.59 -- 0.83    |  52           | [Fu et al. (2010)](https://ui.adsabs.harvard.edu/abs/2010ApJ...722..653F/abstract) |
|  64        | --             | Keck/KCWI                   | (G) Opt             | 2.91 -- 2.92    |  3            | [Daddi et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...649A..78D/abstract) |
|  65        | KMOS$^{3D}$    | VLT/KMOS                    | (G) NIR             | 0.38 -- 2.58    |  296          | [Wisnioski et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...886..124W/abstract) |
|  66        | --             | VLT/KMOS                    | (G) NIR             | 0.22 -- 0.90    |  10           | PI: Antonello Calabrò |
|  67        | KASH$z$        | VLT/KMOS                    | (G) NIR             | 1.10 -- 1.63    |  15           | [Harrison et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.456.1195H/abstract) |
|  68        | KROSS          | VLT/KMOS                    | (G) NIR             | 2.49 -- 2.51    |  16           | [Stott et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.457.1888S/abstract) |
|  69        | LAGER          | Keck/LRIS                   | (G) Opt             | 6.90 -- 6.94    |  11           | [Harish et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...934..167H/abstract) |
|  70        | LAGER          | Magellan/IMACS              | (G) Opt             | 6.88 -- 6.94    |  6            | [Hu et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...845L..16H/abstract) |
|  71        | LAGER          | Magellan/IMACS \& LDSS3     | (G) Opt             | 6.90 -- 6.97    |  16           | [Hu et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021NatAs...5..485H/abstract) |
|  72        | LEGA-C DR3     | VLT/VIMOS                   | (G) Opt             | 0.10 -- 4.31    |  3928         | [van der Wel et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021ApJS..256...44V/abstract) |
|  73        | --             | Keck/LRIS                   | (G) Opt             | 0.00 -- 4.54    |  447          | [Casey et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJ...761..140C/abstract) |
|  74        | --             | Keck/LRIS                   | (G) Opt             | 2.27 -- 3.03    |  58           | [Lee et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...817..160L/abstract) |
|  75        | --             | LBT/LUCI1                   | (G) NIR             | 1.37 -- 2.22    |  11           | [Maseda et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014ApJ...791...17M/abstract) |
|  76        | --             | LBT/LUCI                    | (G) NIR             | 2.15 -- 2.20    |  31           | [Polletta et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...654A.121P/abstract) |
|  77        | M2FS           | Magellan/M2FS               | (G) Opt             | 5.99 -- 6.15    |  3            | [Fu et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...963...51F/abstract) |
|  78        | M2FS           | Magellan/M2FS               | (G) Opt             | 5.64 -- 5.76    |  52           | [Ning et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...903....4N/abstract) |
|  79        | M2FS           | Magellan/M2FS               | (G) Opt             | 6.54 -- 6.63    |  7            | [Ning et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...926..230N/abstract) |
|  80        | MAGAZ3NE       | Keck/MOSFIRE                | (G) NIR             | 3.33 -- 3.43    |  22           | [McConachie et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...926...37M/abstract) |  
|  81        | --             | Magellan/FIRE               | (G) NIR             | 0.37 -- 0.95    |  25           | [Calabrò et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJ...862L..22C/abstract) |
|  82        | MAGIC          | VLT/MUSE                    | (G) Opt             | 0.00 -- 6.61    |  2471         | [Epinat et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...683A.205E/abstract) |
|  83        | --             | ALMA                        | (G) submm/mm        | 5.85            |  2            | [Casey et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...887...55C/abstract) |
|  84        | --             | MMT/Hectospec               | (G) Opt             | 0.01 -- 2.29    |  291          | [Prescott et al. (2006)](https://ui.adsabs.harvard.edu/abs/2006ApJ...644..100P/abstract) |
|  85        | --             | Magellan/IMACS              | (G) Opt             | 0.19 -- 3.26    |  38           | [Trump et al. (2009)](https://ui.adsabs.harvard.edu/abs/2009ApJ...696.1195T/abstract) |
|  86        | --             | Subaru/MOIRCS               | (G) NIR             | 1.43 -- 1.83    |  18           | [Onodera et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJ...755...26O/abstract) |
|  87        | --             | Subaru/MOIRCS               | (G) NIR             | 1.25 -- 2.09    |  34           | [Onodera et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...808..161O/abstract) |
|  88        | --             | Subaru/MOIRCS               | (G) NIR             | 2.19 -- 3.60    |  21           | [Onodera et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...904..180O/abstract) |
|  89        | --             | Subaru/MOIRCS               | (G) NIR             | 1.46 -- 1.63    |  12           | [Tanaka et al. (2013)](https://ui.adsabs.harvard.edu/abs/2013ApJ...772..113T/abstract) |
|  90        | MOSDEF         | Keck/MOSFIRE                | (G) NIR             | 0.80 -- 4.49    |  616          | [Kriek et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJS..218...15K/abstract) |
|  91        | --             | Keck/MOSFIRE                | (G) NIR             | 2.46 -- 2.49    |  42           | [Casey et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...808L..33C/abstract) |
|  92        | --             | Keck/MOSFIRE                | (G) NIR             | 0.17 -- 3.58    |  32           | [Casey et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...840..101C/abstract) |
|  93        | --             | Keck/MOSFIRE                | (G) NIR             | 2.04 -- 2.99    |  52           | [Darvish et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...892....8D/abstract) |
|  94        | MAGAZ3NE       | Keck/MOSFIRE                | (G) NIR             | 2.06 -- 3.83    |  19           | [Forrest et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...903...47F/abstract), [2022](https://ui.adsabs.harvard.edu/abs/2022ApJ...938..109F/abstract), [2024](https://ui.adsabs.harvard.edu/abs/2024ApJ...977...51F/abstract), McConachie et al, (*in prep*) |     
|  95        | --             | Keck/MOSFIRE                | (G) NIR             | 2.76 -- 2.79    |  4            | [Ito et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...945L...9I/abstract) |
|  96        | --             | Keck/MOSFIRE                | (G) NIR             | 4.53            |  1            | [Kakimoto et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...963...49K/abstract) |
|  97        | --             | Keck/MOSFIRE                | (G) NIR             | 2.97 -- 3.69    |  43           | [Onodera et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...822...42O/abstract) |
|  98        | --             | Keck/MOSFIRE                | (G) NIR             | 2.47 -- 3.78    |  6            | [Schreiber et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018A%26A...618A..85S/abstract) |
|  99        | --             | Keck/MOSFIRE                | (G) NIR             | 0.76 -- 2.43    |  33           | PI: Nick Scoville |
| 100        | --             | Keck/MOSFIRE                | (G) NIR             | 2.14 -- 3.62    |  14           | [Trakhtenbrot et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...825....4T/abstract) |
| 101        | ZFIRE          | Keck/MOSFIRE                | (G) NIR             | 1.97 -- 2.31    |  90           | [Tran et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...834..101T/abstract) |
| 102        | --             | Keck/MOSFIRE                | (G) NIR             | 1.24 -- 3.42    |  151          | Vanderhoof et al. (*in prep*) |
| 103        | SMUVS          | VLT/MUSE                    | (G) Opt             | 0.07 -- 6.30    |  792          | [Rosani et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020A%26A...633A.159R/abstract) |
| 104        | MUSE GTO       | VLT/MUSE                    | (G) Opt             | 1.50 -- 6.53    |  263          | [Schmidt et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...654A..80S/abstract) |         
| 105        | --             | VLT/MUSE                    | (G) Opt             | 0.36 -- 4.61    |  27           | [Ventou et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019A%26A...631A..87V/abstract) |
| 106        | --             | *JWST*/NIRSpec              | (S) NIR             | 14.44           |  1            | [Naidu et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025arXiv250511263N/abstract) |
| 107        | NICE           | NOEMA                       | (G) submm/mm        | 1.64 -- 3.61    |  21           | [Sillassen et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...690A..55S/abstract) |
| 108        | --             | Keck/NIRSPEC                | (G) NIR             | 2.03 -- 2.43    |  6            | PI: Jeyhan Kartaltepe |
| 109        | --             | Keck/NIRSPEC                | (G) NIR             | 3.14 -- 3.37    |  2            | [Marsan et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...842...21M/abstract) |
| 110        | --             | *JWST*/NIRSpec              | (S) NIR             | 7.00            |  1            | [Akins et al. (2025a)](https://ui.adsabs.harvard.edu/abs/2025ApJ...991...37A/abstract) |
| 111        | --             | *JWST*/NIRSpec              | (S) NIR             | 7.04            |  1            | [Akins et al. (2025b)](https://ui.adsabs.harvard.edu/abs/2025ApJ...980L..29A/abstract) |
| 112        | --             | NOEMA, ALMA                 | (G) submm/mm        | 3.55 -- 4.10    |  5            | [Jin et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022A%26A...665A...3J/abstract) |
| 113        | --             | NOEMA, Keck/MOSFIRE         | (G) NIR+submm/mm    | 5.10            |  1            | [Shuntov et al. (2025a)](https://ui.adsabs.harvard.edu/abs/2025A%26A...696L..14S/abstract) |
| 114        | --             | NOEMA, VLT/KMOS             | (G) NIR+submm/mm    | 2.49 -- 2.52    |  17           | [Wang et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...828...56W/abstract) |
| 115        | PRIMUS         | Magellan/IMACS              | (G) Opt             | 0.02 -- 4.60    |  29594        | [Coil et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011ApJ...741....8C/abstract) |
| 116        | QUAIA          | *Gaia*                      | (S) Opt             | 0.18 -- 4.12    |  289          | [Storey-Fisher et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...964...69S/abstract) |
| 117        | REBELS         | ALMA                        | (G) submm/mm        | 6.58 -- 7.68    |  11           | [Bouwens et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...931..160B/abstract) |
| 118        | SDSS DR16      | SFT \& du Pont              | (G) Opt             | 0.00 -- 6.58    |  1579         | [Ahumada et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJS..249....3A/abstract) |
| 119        | --             | VLT/SINFONI                 | (G) Opt             | 0.97 -- 2.45    |  5            | [Perna et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015A%26A...583A..72P/abstract) |
| 120        | --             | VLT/VIMOS                   | (G) Opt             | 0.69 -- 0.79    |  619          | [Iovino et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016A%26A...592A..78I/abstract) |
| 121        | --             | VLT/VIMOS 		            | (G) Opt             | 0.89 -- 2.09    |  34           | [Gobat et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017A%26A...599A..95G/abstract) |
| 122        | VIS$^{3}$COS   | VLT/VIMOS                   | (G) Opt             | 0.02 -- 3.59    |  696          | [Paulino-Afonso et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018A%26A...620A.186P/abstract) |
| 123        | VUDS DR1       | VLT/VIMOS                   | (G) Opt             | 0.02 -- 6.44    |  384          | [Le Fèvre et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015A%26A...576A..79L/abstract); [Tasca et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017A%26A...600A.110T/abstract) | 
| 124        | VUDS DR2&ast;  | VLT/VIMOS                   | (G) Opt             | 0.02 -- 6.44    |  4703         | Tasca et al., (*in prep*) | 
| 125        | WERLS          | Keck/MOSFIRE                | (G) NIR             | 3.52 -- 6.93    |  83           | PIs: Caitlin Casey & Jeyhan Kartaltepe |
| 126        | WERLS          | Keck/MOSFIRE                | (G) NIR             | 0.51 -- 8.23    |  192          | [Cooper et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...970...50C/abstract) |
| 127        | --             | {\it HST}/WFC3              | (S) NIR             | 2.39 -- 3.23    |  10           | [D'Eugenio et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...653A..32D/abstract) | ADD LUSTIG2021
| 128        | --             | {\it HST}/WFC3              | (S) NIR             | 0.68 -- 2.18    |  150          | Based on 3D-*HST* data |
| 129        | --             | {\it HST}/WFC3              | (S) NIR             | 1.84 -- 2.20    |  14           | [Krogager et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014ApJ...797...17K/abstract) |
| 130        | XLS            | VLT/X-SHOOTER               | (G) Opt+NIR         | 2.07 -- 2.47    |  18           | [Matthee et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021MNRAS.505.1382M/abstract) |
| 131        | *XMM*-COSMOS   | VLT/X-SHOOTER               | (G) Opt+NIR         | 1.00 -- 1.60    |  10           | [Brusa et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015MNRAS.446.2394B/abstract) |   
| 132        | CALYMHA        | VLT/X-SHOOTER               | (G) Opt+NIR         | 2.21 -- 2.23    |  3            | [Sobral et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018MNRAS.477.2817S/abstract) |
| 133        | --             | VLT/X-SHOOTER               | (G) Opt+NIR         | 1.96 -- 2.69    |  14           | [Stockmann et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...888....4S/abstract) |
| 134        | --             | VLT/X-SHOOTER               | (G) Opt             | 3.78            |  1            | [Valentino et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...889...93V/abstract) |
| 135        | hCOSMOS        | MMT/Hectospec               | (G) Opt             | 0.00 -- 1.27    |  4399         | [Damjanov et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJS..234...21D/abstract) |
| 136        | zCOSMOS Bright | VLT/VIMOS                   | (G) Opt             | 0.00 -- 4.45    |  20716        | [Lilly et al. (2007)](https://ui.adsabs.harvard.edu/abs/2007ApJS..172...70L/abstract), [2009](https://ui.adsabs.harvard.edu/abs/2009ApJS..184..218L/abstract) |
| 137        | zCOSMOS Deep   | VLT/VIMOS                   | (G) Opt             | 0.00 -- 4.25    |  9371         | PI: Simon Lilly |
| 138        | zFIRE          | Keck/MOSFIRE                | (G) NIR             | 1.97 -- 3.53    |  216          | [Nanayakkara et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...828...21N/abstract) |  
</div>

&ast; VUDS DR2 is currently proprietary but is expected to be released soon upon completion of the survey paper and the VUDS team official release. This data set will be included upon its public release.