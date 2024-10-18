## Data from: Benthic drivers of structural complexity in coral reefs across a tropical-subtropical transition zone

This README file was generated on 18th-Jan-2024 by Meng-Hsin Morris Wu (tapewormwu@gmail.com). Knit Data_Analysis_Script.Rmd to generate html and extract R code.

1. **Author Information**

First author name: Mr. Meng-Hsin Morris Wu. Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan

Second author name: Dr. Lauriane Ribas-Deulofeu. Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan; Ocean Center, National Taiwan University, Taipei 10617, Taiwan.

Third author name: Mr. Chia-Hung Eric Liu. Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan.

Fourth author name: Prof. Yoko Nozawa. Affiliation: Tropical Biosphere Research Center, University of the Ryukyus, Okinawa 905-0227, Japan; Department of Marine Science, Faculty of Fisheries and Marine Science, Universitas Diponegoro, Semarang, Indonesia.

Fifth & corresponding author name: Prof. Vianney Denis Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan; Ocean Center, National Taiwan University, Taipei 10617, Taiwan. Email: vianneydenis@ntu.edu.tw

2. **Date of data collection:** 2023

3. **Geographic location of data collection:** southern, eastern, and northern Taiwan, West Pacific

4. **Funding sources that supported the collection of the data:** Ocean Conservation Administration of Taiwan, Ministry of Science and Technology of Taiwan

5. **Recommended citation for this dataset:** Wu, Meng-Hsin Morris; Ribas-Deulofeu, Lauriane; Liu, Chia-Hung Eric; Nozawa, Yoko; Denis, Vianney (2024), Data from: Benthic drivers of structural complexity in coral reefs across a tropical-subtropical transition zone, Dryad, Dataset, DOI: XXXX


***DESCRIPTION OF THE DATA AND FILE STRUCTURE***

-------------------------------------------------------------

**DATA & FILE OVERVIEW**

*1. Description of dataset*

These data were generated to express structural complexity and the composition of benthic communities over plots across tropical-subtropical transition in Taiwan.

*2. File list*

There are four spreadsheets in the folder **Data**.

File 1 complexity_metrics.csv; File 1 description: Complexity metrics of each site.

File 2 composition_substrates.csv; File 2 description: Benthic composition of each site.

File 3 coordinates.xlsx; File 3 description: The longitude and latitude of each site.

File 4 model_quality.xlsx; File 4 description: Quality of the 3D models reconstructed from sites. 


***METHODOLOGICAL INFORMATION***

A detailed description of data acquisition and processing can be found in the published manuscript in the JOURNAL NAME (DOI).


**DATA-SPECIFIC INFORMATION**

*complexity_metrics.csv*

1. Number of variables/columns: 25

2. Number of cases/rows: 25

3. Missing data codes: None

4. Variable List

* Column A: Abbreviated site names.The full site name corresponding to the abbreviation are described as below.

|  Acronym in complexity_metrics.csv   | Full site name  |
|  ----  | ----  |
| 82.5 | 82.5K  |
| BT  | Bitou |
| CCG  | GreenGrassland |
| CJ  |  Chaojing  |
|  CK  | Chaikou  |
|  DaBS  |  Dabaisha  |
| DC  |  Dongchin  |
|  DiBS  |  Dinbaisha  |
|  FNL  |  Fenniaolin |
|  GGB  |  Gongguanbi  |
|GW|Guiwan|
|HBH|Houbihu|
|HR|HenRock|
|HS|Hsinshe|
|JH|Jihui|
|JLS|Jialeshui|
|JMZ|Jiamuziwan|
|JQ|Jiqi|
|LD|Longdong|
|LDS|Leidashih|
|MYS|Meiyenshan|
|SL|Shihlang|
|TL|TwoLins|
|TS|Tiaoshih|
|YY|Yayo|

* Column B - S4: Value of S - 4 cm at each site.
* Column C - T4: Value of TRI - 4 cm at each site. 
* Column D - V4: Value of VRM - 4 cm at each site.
* Column E - S32: Value of S - 32 cm at each site.
* Column F - T32: Value of TRI - 32 cm at each site.
* Column G - V32: Value of VRM - 32 cm at each site.
* Column H - PROC4: Value of PROC - 4 cm at each site.
* Column I - PLC4: Value of PLC - 4 cm at each site.
* Column J - PROC32: Value of PROC - 32 cm at each site.
* Column K - PLC32: Value of PLC - 32 cm at each site.
* Column L - S16: Value of S - 16 cm at each site.
* Column M - T16: Value of TRI - 16 cm at each site.
* Column N - V16: Value of VRM - 16 cm at each site.
* Column O - PROC16: Value of PROC - 16 cm at each site.
* Column P - PLC16: Value of PLC - 16 cm at each site.
* Column Q - D64: Value of D (1 - 64 cm) at each site.
* Column R - SC: Value of SC at each site.
* Column S - D1_2: Value of D (1 - 2 cm) at each site.
* Column T - D2_4: Value of D (2 - 4 cm) at each site.
* Column U - D4_8: Value of D (4 - 8 cm) at each site.
* Column V - D8_16: Value of D (8 - 16 cm) at each site.
* Column W - D16_32: Value of D (16 - 32 cm) at each site.
* Column X - D32_64: Value of D (32 - 64 cm) at each site.
* Column Y - VRSD: Value of Sq at each site.
* Column Z - region: The region where each site nests in. Abbreviation used:

|  Region abbreviation in complexity_metrics.csv   | Full regional name  |
|  ----  | ----  |
|KT| Kenting  |
|LY| Lanyu |
|LD| Ludao |
|EC|East Coast|
|NC|North Coast|


*composition_substrates.csv*

1. Number of variables/columns: 32

2. Number of cases/rows: 26

3. Missing data codes: None

4. Variable List

* Column A - site: Abbreviated site names.
* Column B - region: Abbreviated regional names.
* Column C - actinia: Benthic cover of sea anemone (AN) at each site.
* Column D - hcarb: Benthic cover of arborescent hard corals (Arborescent HC) at each site.
* Column E - hcbus: Benthic cover of bushy hard corals (Bushy HC) at each site.
* Column F - hccol: Benthic cover of columnar hard corals (Columnar HC) at each site.
* Column G - hcenc: Benthic cover of encrusting hard corals (Encrusting HC) at each site.
* Column H - hcfol: Benthic cover of foliose hard corals (Foliose HC) at each site.
* Column I - hcmas: Benthic cover of massive hard corals (Massive HC) at each site.
* Column J - hctab: Benthic cover of tabular hard corals (Tabular HC) at each site.
* Column K - ocdig: Benthic cover of digitate octocorals (Digitate OC) at each site.
* Column L - oclob: Benthic cover of lobate octocorals (Lobate oc) at each site.
* Column M - ocmas: Benthic cover of massive octocorals (Massive OC) at each site.
* Column N - tws: Benthic cover of marine debris (MD) at each site.
* Column O - fil: Benthic cover of turfs (TU) at each site.
* Column P - ocbus: Benthic cover of bushy octocorals (Bushy OC) at each site.
* Column Q - ascidian: Benthic cover of ascidian (AS) at each site.
* Column R - ocfan: Benthic cover of fan-liked octocorals (Fan-liked OC) at each site.
* Column S - zoaenc: Benthic cover of encrusting zoanthids (Encrusting ZO) at each site.
* Column T - spoglo: Benthic cover of globular sponges (Globular SP) at each site.
* Column U - spomas: Benthic cover of massive sponges (Massive SP) at each site.
* Column V - zoamas: Benthic cover of massive zoanthids (Massive ZO) at each site.
* Column W - occlu: Benthic cover of clustered octocorals (Clustered OC) at each site.
* Column X - ocenc: Benthic cover of encrusting octocorals  (Encrusting OC) at each site.
* Column Y - other: Benthic cover of motil life (OL) at each site.
* Column Z - sporep: Benthic cover of repent sponges (Repent SP) at each site.
* Column AA - spopap: Benthic cover of papillate sponges (Repent SP) at each site.
* Column AB - coeenc: Benthic cover of corallimorpharian (CO) at each site.
* Column AC - cru_or_spoenc: Benthic cover of crustose coralline algae (CCA) at each site.
* Column AD - bss: Benthic cover of bare stable substrate (BSS) at each site.
* Column AE - ma: Benthic cover of macroalgae (MA) at each site.
* Column AF - us: Benthic cover of unstable substrates (US) at each site.

*coordinates.xlsx*

1. Number of variables/columns: 3

2. Number of cases/rows: 26

3. Missing data codes: None

4. Variable List

* Column A - Site: Abbreviated site names.
* Column B - Lat: Latitude of each site.
* Column C - Long: Longitude each site.

*model_quality.xlsx*

1. Number of variables/columns: 6

2. Number of cases/rows: 26

3. Missing data codes: None

4. Variable List

* Column A - site: Abbreviated site names.
* Column B - images: Number of images used in 3D reconstruction at each site.
* Column C - Res_mm: Pixel size of orthomosaic and Digital Elevated Model (DEM) of each site. Millimeter is the default unit.
* Column D - Reproj_Error: The reprojection error in 3D reconstruction of each site. Pixel is the default unit.
* Column E - Cont_Error: The control error in 3D reconstruction of each site. Pixel is the default unit.
* Column F - PLA: The planar area orthomosaic and DEM cover at each site.
