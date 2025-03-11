## List of Surveys Included in the Compilation

The compilation consists of three key files: 
-   `_all.fits`: corresponds to all redshift measurements
-   `_unique.fits`: corresponds to all unique sources with those having duplicate redshift measurements having their best spectroscopic redshift assigned based on the highest quality flag. In the case where a source has 2 redshifts of equal quality flag, we assign the most recent redshift as the 'best' spectroscopic redshift
-   `_surveys.list`: an ASCII file that contains the survey ID number assigned in the FITS files under the column `survey', the survey name, a simple reference placeholder, status of the survey, contact information for PI, number of galaxies in the survey, and key statistics on the redshift distribution.

For convenience, we outline the survey information with links to their respective publications. In the case only a portion of the compilation is used, we highly encourage users (if possible) to cite the references associated with the programs for which the redshifts are drawn from in addition to our compilation publication.

<div style="overflow-x:auto; font-size: 12px;">

| Survey ID  | Survey Name    | Telescope/Instrument        | Redshift Range  | # of Galaxies | Reference(s) or PI |
| -----------| -------------- |  ---------------------      | --------------- |  ------------ |  ---------------   |  
|   1        | 2dFGRS         | AAT/2dF                     | 0.00 -- 0.33    |  222          | [Colless et al. (2001)](https://ui.adsabs.harvard.edu/abs/2001MNRAS.328.1039C/abstract) |
|   2        | 3DHST          | *HST*/WFC3 & *HST*/ACS      | 0.00 -- 1.34    |  455          | [Brammer et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJS..200...13B/abstract), [Momcheva et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJS..225...27M/abstract) |
|   3        |   --           | AAT                         | 0.00 -- 3.29    |  636          | Suzuki et al., (*in prep*) |
|   4        |   --           | ALMA                        | 4.32 - 4.33     |  2            | [Brinch et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025A%26A...694A.218B/abstract) |
|   5        |   --           | ALMA                        | 3.62 -- 5.85    |  4            | [Jin et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...887..144J/abstract) |
|   6        |   --           | ALMA                        | 2.625           |  1            | [Jin et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...690L..16J/abstract) |
|   7        |   --           | ALMA                        | 6.75 -- 7.06    |  3            | [Schouws et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...954..103S/abstract) |
|   8        |   --           | ALMA                        | 4.820           |  1            | [Sillassen et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025A%26A...693A.309S/abstract) |
|   9        |   --           | ALMA                        | 6.81 -- 6.85    |  2            | [Smit et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018Natur.553..178S/abstract) |
|  10        |   --           | ALMA                        | 1.15 -- 1.63    |  55           | [Valentino et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJ...869...27V/abstract), [2020a](https://ui.adsabs.harvard.edu/abs/2020ApJ...890...24V/abstract), [2020b](https://ui.adsabs.harvard.edu/abs/2020A%26A...641A.155V/abstract) |
|  11        | AS2COSPEC      | ALMA                        | 1.90 -- 4.78    |  18           | [Chen et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...931..160B/abstract) |
|  12        | AzTEC COSMOS   | LMT/RSR & SMA/SIS           | 4.34            |  1            | [Yun et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015MNRAS.454.3485Y/abstract) |
|  13        | AzTEC COSMOS   | ALMA & NOEMA                | 4.63            |  2            | [Jimenez et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...890..171J/abstract) |
|  14        | BRiZELS	      | WHT/LIRIS \& TNG/NICS       | 0.84 -- 2.28    |  17           | [Sobral et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.457.1739S/abstract) |
|  15        | C3R2-DR3       | Keck/LRIS, DEIMOS, MOSFIRE  | 0.10 -- 4.17    |  347          | [Stanford et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021ApJS..256....9S/abstract) |
|  16        | C3R2-LBT       | LBT/LUCI1, LUCI2            | 1.32 -- 2.56    |  163          | [Saglia et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022A%26A...664A.196E/abstract) |
|  17        | C3R2           | Keck/LRIS, DEIMOS, MOSFIRE  | 0.00 -- 4.50    |  2869         | [Masters et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...841..111M/abstract), [2019](https://ui.adsabs.harvard.edu/abs/2019ApJ...877...81M/abstract) |
|  18        | CANDELSz7      | VLT/FORS2                   | 0.66 -- 7.14    |  18           | [Pentericci et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018A%26A...619A.147P/abstract) |
|  19        | CHESS          | Keck/DEIMOS                 | 0.08 -- 1.61    |  233          | Lertprasertpong et al., (*in prep*) |
|  20        | CLAMATO DR2    | Keck/LRIS                   | 0.05 -- 3.52    |  600          | [Lee et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJS..237...31L/abstract), [Horowitz et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJS..263...27H/abstract) |
|  21        | --             | MMT/Binospec                | 6.70 -- 6.88    |  9            | [Endsley et al. (2021)](https://ui.adsabs.harvard.edu/abs/2022MNRAS.511.6042E/abstract) | 
|  22        | --             | Keck/DEIMOS                 | 0.37 -- 6.32    |  22           | [Brinch et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024MNRAS.527.6591B/abstract)  |
|  23        | --             | Keck/DEIMOS                 | 0.03 -- 6.47    |  3158         | PI: Peter Capak |
|  24        | --             | Keck/DEIMOS                 | 0.12 -- 1.52    |  156          | [Casey et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJ...761..140C/abstract) |
|  25        | 10K-DEIMOS     | Keck/DEIMOS                 | 0.00 -- 6.60    |  10718        | [Hasinger et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJ...858...77H/abstract) |
|  26        | --             | Keck/DEIMOS                 | 0.00 -- 5.04    |  1059         | [Kartaltepe et al. (2010)](https://ui.adsabs.harvard.edu/abs/2010ApJ...709..572K/abstract) |
|  27        | --             | Keck/DEIMOS                 | 0.39 -- 5.01    |  143          | PI: Mara Salvato |
|  28        | --             | Keck/DEIMOS                 | 0.08 -- 1.76    |  225          | [Shah et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...904..107S/abstract) |
|  29        | DESI-EDR       | Mayall/DESI                 | 0.00 -- 5.81    |  44827        | [Adame et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024AJ....168...58D/abstract) |
|  30        | FENIKS         | Keck/MOSFIRE                | 3.34 -- 4.67    |  4            | [Antwi-Danso et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025ApJ...978...90A/abstract) |
|  31        | FMOS--COSMOS   | Subaru/FMOS                 | 0.37 -- 4.64    |  988          | [Kartaltepe et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...806L..35K/abstract) | 
|  32        | FMOS--COSMOS   | Subaru/FMOS                 | 0.70 -- 2.59    |  5484         | [Kashino et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJS..241...10K/abstract) |
|  33        | --             | Subaru/FMOS                 | 0.60 -- 1.45    |  539          | PI: Tohru Nagao |
|  34        | --             | Subaru/FMOS                 | 0.68 -- 1.57    |  85           | [Roseboom et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012MNRAS.426.1782R/abstract) |
|  35        | --             | Subaru/FOCAS                | 0.05 -- 3.88    |  114          | PI: Tohru Nagao |
|  36        | --             | VLT/FORS2                   | 0.08 -- 5.49    |  1767         | [Comparat et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015A%26A...575A..40C/abstract) |
|  37        | --             | VLT/FORS2                   | 2.44 -- 2.45    |  11           | [Diener et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...802...31D/abstract) |
|  38        | --             | VLT/FORS2                   | 0.04 -- 1.29    |  530          | [George et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011ApJ...742..125G/abstract) |
|  39        | --             | VLT/FORS1                   | 0.03 -- 1.15    |  54           | [Faure et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011A%26A...529A..72F/abstract) |      
|  40        | GEEC2          | Gemini-S/GMOS               | 0.12 -- 1.51    |  807          | [Balogh et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011MNRAS.412.2303B/abstract) |
|  41        | --             | Gemini-S/GMOS               | 0.10 -- 1.66    |  124          | Cox et al. (*in prep*) |
|  42        | GOGREEN-DR1    | Gemini/GMOS                 | 0.50 -- 2.32    |  226          | [Balogh et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021MNRAS.500..358B/abstract) |
|  43        | --             | MMT/Hectospec               | 0.00 -- 1.44    |  277          | [Sohn et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...880..142S/abstract) |
|  44        | HETDEX-DR2     | HET/VIRUS                   | 0.01 -- 3.51    |  2447         | [Mentuch Cooper et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...943..177M/abstract) |
|  45        | HETVIPS        | HET/VIRUS                   | 0.00 -- 2.10    |  325          | [Zeimann et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...966...14Z/abstract) |
|  46        | HR-COSMOS      | VLT/VIMOS                   | 0.74 -- 1.18    |  82           | [Pelliccia et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017A%26A...599A..25P/abstract) | 
|  47        | --             | Magellan/IMACS              | 0.00 -- 4.66    |  2858         | [Trump et al. (2007)](https://ui.adsabs.harvard.edu/abs/2007ApJS..172..383T/abstract) |
|  48        | --             | \it{Spitzer}/IRS            | 0.59 -- 0.83    |  52           | [Fu et al. (2010)](https://ui.adsabs.harvard.edu/abs/2010ApJ...722..653F/abstract) |
|  49        | KMOS$^{3D}$    | VLT/KMOS                    | 0.38 -- 2.58    |  296          | [Wisnioski et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...886..124W/abstract) |
|  50        | --             | VLT/KMOS                    | 0.22 -- 0.90    |  10           | PI: Antonello Calabrò |
|  51        | KASH$z$        | VLT/KMOS                    | 1.10 -- 1.63    |  15           | [Harrison et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.456.1195H/abstract) |
|  52        | KROSS          | VLT/KMOS                    | 2.49 -- 2.51    |  16           | [Stott et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.457.1888S/abstract) |
|  53        | LAGER          | Keck/LRIS                   | 6.90 -- 6.94    |  11           | [Harish et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...934..167H/abstract) |
|  54        | LAGER          | Magellan/IMACS              | 6.88 -- 6.94    |  6            | [Hu et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...845L..16H/abstract) |
|  55        | LAGER          | Magellan/IMACS \& LDSS3     | 6.90 -- 6.97    |  16           | [Hu et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021NatAs...5..485H/abstract) |
|  56        | LEGA-C DR3     | VLT/VIMOS                   | 0.10 -- 4.31    |  3928         | [van der Wel et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021ApJS..256...44V/abstract) |
|  57        | --             | Keck/LRIS                   | 0.00 -- 4.54    |  447          | [Casey et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012ApJ...761..140C/abstract) |
|  58        | --             | LBT/LUCI1                   | 1.37 -- 2.22    |  11           | [Maseda et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014ApJ...791...17M/abstract) |
|  59        | M2FS           | Magellan/M2FS               | 5.64 -- 5.76    |  52           | [Ning et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...903....4N/abstract) |
|  60        | MAGAZ3NE       | Keck/MOSFIRE                | 3.33 -- 3.43    |  22           | [McConachie et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...926...37M/abstract) |  
|  61        | --             | Magellan/FIRE               | 0.37 -- 0.95    |  25           | [Calabrò et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJ...862L..22C/abstract) |
|  62        | MAGIC          | VLT/MUSE                    | 0.00 -- 6.61    |  2471         | [Epinat et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...683A.205E/abstract) |
|  63        | --             | ALMA                        | 5.85            |  2            | [Casey et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...887...55C/abstract) |
|  64        | --             | MMT/Hectospec               | 0.01 -- 2.29    |  291          | [Prescott et al. (2006)](https://ui.adsabs.harvard.edu/abs/2006ApJ...644..100P/abstract) |
|  65        | --             | Magellan/IMACS              | 0.19 -- 3.26    |  38           | [Trump et al. (2009)](https://ui.adsabs.harvard.edu/abs/2009ApJ...696.1195T/abstract) |
|  66        | --             | Subaru/MOIRCS               | 1.25 -- 2.09    |  34           | [Onodera et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...808..161O/abstract) |
|  67        | --             | Subaru/MOIRCS               | 2.19 -- 3.60    |  21           | [Onodera et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...904..180O/abstract) |
|  68        | --             | Subaru/MOIRCS               | 1.46 -- 1.63    |  12           | [Tanaka et al. (2013)](https://ui.adsabs.harvard.edu/abs/2013ApJ...772..113T/abstract) |
|  69        | MOSDEF         | Keck/MOSFIRE                | 0.80 -- 4.49    |  616          | [Kriek et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJS..218...15K/abstract) |
|  70        | --             | Keck/MOSFIRE                | 2.04 -- 2.99    |  52           | [Darvish et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...892....8D/abstract) |
|  71        | MAGAZ3NE       | Keck/MOSFIRE                | 2.06 -- 3.83    |  19           | [Forrest et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...903...47F/abstract), [2022](https://ui.adsabs.harvard.edu/abs/2022ApJ...938..109F/abstract), [2024](https://ui.adsabs.harvard.edu/abs/2024ApJ...977...51F/abstract), McConachie et al, (*in prep*) |
|  72        | --             | Keck/MOSFIRE                | 2.76 -- 2.79    |  4            | [Ito et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...945L...9I/abstract) |
|  73        | --             | Keck/MOSFIRE                | 2.97 -- 3.69    |  43           | [Onodera et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...822...42O/abstract) |
|  74        | --             | Keck/MOSFIRE                | 2.47 -- 3.78    |  6            | [Schreiber et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018A%26A...618A..85S/abstract) |
|  75        | --             | Keck/MOSFIRE                | 0.76 -- 2.43    |  33           | PI: Nick Scoville |
|  76        | --             | Keck/MOSFIRE                | 2.14 -- 3.62    |  14           | [Trakhtenbrot et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...825....4T/abstract) |
|  77        | ZFIRE          | Keck/MOSFIRE                | 1.97 -- 2.31    |  90           | [Tran et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...834..101T/abstract) |
|  78        | --             | Keck/MOSFIRE                | 1.24 -- 3.42    |  151          | Vanderhoof et al. (*in prep*) |
|  79        | SMUVS          | VLT/MUSE                    | 0.07 -- 6.30    |  792          | [Rosani et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020A%26A...633A.159R/abstract) |
|  80        | MUSE GTO       | VLT/MUSE                    | 1.50 -- 6.53    |  263          | [Schmidt et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...654A..80S/abstract) |         
|  81        | --             | VLT/MUSE                    | 0.36 -- 4.61    |  27           | [Ventou et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019A%26A...631A..87V/abstract) |
|  82        | NICE           | NOEMA                       | 1.64 -- 3.61    |  21           | [Sillassen et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...690A..55S/abstract) |
|  83        | --             | Keck/NIRSPEC                | 2.03 -- 2.43    |  6            | PI: Jeyhan Kartaltepe |
|  84        | --             | Keck/NIRSPEC                | 3.14 -- 3.37    |  2            | [Marsan et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...842...21M/abstract) |
|  85        | --             | NOEMA, ALMA                 | 3.55 -- 4.10    |  5            | [Jin et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022A%26A...665A...3J/abstract) |
|  86        | PRIMUS         | Magellan/IMACS              | 0.02 -- 4.60    |  29594        | [Coil et al. (2011)](https://ui.adsabs.harvard.edu/abs/2011ApJ...741....8C/abstract) |
|  87        | QUAIA          | *Gaia*                      | 0.18 -- 4.12    |  289          | [Storey-Fisher et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...964...69S/abstract) |
|  88        | REBELS         | ALMA                        | 6.58 -- 7.68    |  11           | [Bouwens et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJ...931..160B/abstract) |
|  89        | SDSS DR16      | SFT \& du Pont              | 0.00 -- 6.58    |  1579         | [Ahumada et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJS..249....3A/abstract) |
|  90        | --             | VLT/SINFONI                 | 0.97 -- 2.45    |  5            | [Perna et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015A%26A...583A..72P/abstract) |
|  91        | --             | VLT/VIMOS                   | 0.69 -- 0.79    |  619          | [Iovino et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016A%26A...592A..78I/abstract) |
|  92        | --             | VLT/VIMOS 		            | 0.89 -- 2.09    |  34           | [Gobat et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017A%26A...599A..95G/abstract) |
|  93        | VIS$^{3}$COS   | VLT/VIMOS                   | 0.02 -- 3.59    |  696          | [Paulino-Afonso et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018A%26A...620A.186P/abstract) |
|  94        | VUDS&ast;           | VLT/VIMOS                   | 0.02 -- 6.44    |  4629         | [Le Fèvre et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015A%26A...576A..79L/abstract); [Tasca et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017A%26A...600A.110T/abstract) | 
|  95        | WERLS          | Keck/MOSFIRE                | 3.52 -- 6.93    |  83           | PIs: Caitlin Casey & Jeyhan Kartaltepe |
|  96        | WERLS          | Keck/MOSFIRE                | 0.51 -- 8.23    |  192          | [Cooper et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...970...50C/abstract) |
|  97        | --             | {\it HST}/WFC3              | 2.39 -- 3.23    |  10           | [D'Eugenio et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...653A..32D/abstract) |
|  98        | --             | {\it HST}/WFC3              | 0.68 -- 2.18    |  150          | Based on 3D-*HST* data |
|  99        | --             | {\it HST}/WFC3              | 1.84 -- 2.20    |  14           | [Krogager et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014ApJ...797...17K/abstract) |
| 100        | XLS            | VLT/X-SHOOTER               | 2.07 -- 2.47    |  18           | [Matthee et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021MNRAS.505.1382M/abstract) |
| 101        | *XMM*-COSMOS   | VLT/X-SHOOTER               | 1.00 -- 1.60    |  10           | [Brusa et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015MNRAS.446.2394B/abstract) |   
| 102        | CALYMHA        | VLT/X-SHOOTER               | 2.21 -- 2.23    |  3            | [Sobral et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018MNRAS.477.2817S/abstract) |
| 103        | --             | VLT/X-SHOOTER               | 1.96 -- 2.69    |  14           | [Stockmann et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...888....4S/abstract) |
| 104        | --             | VLT/X-SHOOTER               | 3.78            |  1            | [Valentino et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJ...889...93V/abstract) |
| 105        | hCOSMOS        | MMT/Hectospec               | 0.00 -- 1.27    |  4399         | [Damjanov et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJS..234...21D/abstract) |
| 106        | zCOSMOS Bright | VLT/VIMOS                   | 0.00 -- 4.45    |  20716        | [Lilly et al. (2007)](https://ui.adsabs.harvard.edu/abs/2007ApJS..172...70L/abstract), [2009](https://ui.adsabs.harvard.edu/abs/2009ApJS..184..218L/abstract) |
| 107        | zCOSMOS Deep   | VLT/VIMOS                   | 0.00 -- 4.25    |  9371         | PI: Simon Lilly |
| 108        | zFIRE          | Keck/MOSFIRE                | 1.97 -- 3.53    |  216          | [Nanayakkara et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016ApJ...828...21N/abstract) |  
</div>

&ast; Note that the VUDS data only contains the DR1 release (~380 sources) while DR2 will fully contain 4629 sources in total. Given that the VUDS DR2 is still proprietary at the moment, we ask that if anyone is interested in using this specific dataset that they contact the VUDS team. In the meantime, placeholders are set for the VUDS DR2 targets (zspec = 100 and *Q<sub>f</sub>* = 100)