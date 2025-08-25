#### TPChange data sets

**as of: 2025-08-22**
*last editor: dkunkel*

| Field              | Description                                                          |
| ------------------ | -------------------------------------------------------------------- |
| project ID         | TPC project number                                                   |
| shortname          | name of data set                                                     |
| type               | model / experimental / satellite                                     |
| format             | format of data set                                                   |
| coverage           | coverage / resolution of data set                                    |
| owner/source       | original source (if data have been retrieved from somewhere)         |
| retrieval/creation | time when data set has been retrieved from source / has been created |
| version            | if applicable, version number of data set                            |
| contact            | contact person                                                       |

| project ID | shortname | type | format | coverage | owner/source | retrieval/creation | version | contact | additional information |
| ---------- | --------- | ---- | ------ | -------- | ------------ | ------------------ | ------- | ------- | ---------------------- |
| A01        |           |      |        |          |              |                    |         |         | |
| A02        |           |      |        |          |              |                    |         |         | |
| A03        | TPex mc-CPC data | obs data | NASA AMES | 2024/06/07-2024/06/20; 0-12 km alt.; Northern Germany, Southern Scandinavia | GUF, [seafile](https://seafile.rlp.net/d/fbb87dcfe42e43cf9f45) | creation: 2024/10/17 | v1, preliminary | [Sarah Richter](richter@iau.uni-frankfurt.de) | part of TPex merged data set on [zenodo](https://doi.org/10.5281/zenodo.15371527) |
| A04        | ACCLIP ERICA-AMS          | obs. data     | NASA ICAART       | 2022/08/04- 2022/08/31; 0-16 km alt.; 124°E-150°W & 15°N-61.5°N  | MPIC, [public](https://doi.org/10.26023/T7RT-01YD-A110) | creation: 2023-03-22  | v1 | [Oliver Eppers](o.eppers@mpic.de)  |ERICA-AMS in-situ data obtained from the [Asian Summer Monsoon Chemical & CLimate Impact Project (ACCLIP) mission](https://www.eol.ucar.edu/field_projects/acclip) |
| A04        | ACCLIP ERICA-LAMS          | obs. data     | NASA ICAART       | 2022/07/31- 2022/08/31; 0-16 km alt.; 124°E-150°W & 15°N-61.5°N  | MPIC, [public](https://doi.org/10.26023/BN0Z-CHGG-PD0B) | creation: 2023-03-24  | v1 | [Oliver Eppers](o.eppers@mpic.de)  |ERICA-LAMS in-situ data obtained from the [Asian Summer Monsoon Chemical & CLimate Impact Project (ACCLIP) mission](https://www.eol.ucar.edu/field_projects/acclip) |
| A05        |           |      |        |          |              |                    |         |         | |
| A06        |           |      |        |          |              |                    |         |         | |
| A07        |           |      |        |          |              |                    |         |         | |
|            |           |      |        |          |              |                    |         |         | |
| B01        | MECO(n) TPex | mod data | netCDF | 2024/06/01-2024/06/24 , TPex area | JGU-IPA, MOGON2 | 2024/12 | NA | [Chun Hang Chau](cchau@uni-mainz.de) | It is a high vertical resolution simulation in the multi-scale model MECOn, with high horizontal resolution covering the restricted flight area. | |
| B01        | TPEx 2024-F07-LAGRANTO-10days-trajectories | mod data | netCDF | 2024/06/17, TPex area | JGU-IPA, [zenodo](https://doi.org/10.5281/zenodo.16262949) | 2025/07/21 | v1 | [Annette Miltenberger](amiltenb@uni-mainz.de) | | 
| B02        | BISTUM23 Balloon   | obs. data  | ascii (csv)   | 2023/08/04-2023/08/17, Tailfingen, Germany | JGU-IPA, [gitlab](https://gitlab.rlp.net/tpchange/research-area-b/b02/balloncampaign_2023) | 2023/03/21 | final | [Luis Valero Tuya](luistuya@uni-mainz.de) | |
| B02        | BISTUM24 Balloon   | obs. data  | ascii (csv)   | 2024/06/07-2024/06/21, Spielberg, Germany | JGU-IPA, N/A | 2024/08/03 | preliminary | [Luis Valero Tuya](luistuya@uni-mainz.de) | |
| B02        | BISTUM23_MoLa | obs. data | ascii | 2023/08/01-2023/08/18, Taiflingen, Germany | MPIC, [zenodo](https://doi.org/10.5281/zenodo.14748149)   |  2024/08/18 |  final, v1 |  [Lasse Moormann](lasse.moormann@mpic.de)  | Associated with a publication: [Moormann et al. 2024](https://amt.copernicus.org/articles/18/1441/2025/)  |
| B03        |           |      |        |          |              |                    |         |         | |
| B04        |           |      |        |          |              |                    |         |         | |
| B06        |           |      |        |          |              |                    |         |         | |
| B07        |           |      |        |          |              |                    |         |         | |
| B08        |           |      |        |          |              |                    |         |         | |
|            |           |      |        |          |              |                    |         |         | |
| C01        |           |      |        |          |              |                    |         |         | |
| C02        | GUF AirCore Data | obs. data | NASA ICAART | since 2022/09, bi-monthly | GUF, [zenodo](https://doi.org/10.5281/zenodo.15274043)  | ongoing since 2022/09 | v1 (zenodo)  | [Johannes Degen](degen@iau.uni-frankfurt.de) | Associated with [Degen et al. (2025)](https://doi.org/10.5194/egusphere-2025-2648) |
| C02        | NOAA AirCore Data | obs. data | NASA ICAART | 2012-2023 | [GML](https://doi.org/10.15138/6AV0-MY81)  | 2024-08-21 | v20230831  | [Johannes Degen](degen@iau.uni-frankfurt.de) | |
| C02        | EMAC AirCore data | mod. data | netCDF | 1998/01-2024/06, global, 12min sampling | [DKRZ Levante (internal)](/work/bd1305/b309210/4Degen/TPC1SD-2_s4d_AirCore.tar)  | 2024/12 | v202410 | [Johannes Degen](degen@iau.uni-frankfurt.de) | EMAC TPChange specified-dynamics run|
| C03        |  ERA5/ERA5.1   | reanalysis     | netCDF   | 1979-2025, global  |  [ERA5](https://doi.org/10.24381/cds.143582cf), [ERA5.1](https://doi.org/10.24381/cds.143582cf) | unknown | ERA5.1 | [Katharina Turhal](k.turhal@fz-juelich.de) | |
| C03        |  ERA-Interim   | reanalysis     | netCDF   | 1979-2018, global  |  [ERA-Interim](https://doi.org/10.24381/cds.f2f5241d) | unknown | - | [Katharina Turhal](k.turhal@fz-juelich.de) | |
| C03        |  JRA55         | reanalysis     | netCDF   | 1979-2019, global  |  [JRA55](https://doi.org/10.5065/D6HH6H41) | unknown | - | [Katharina Turhal](k.turhal@fz-juelich.de) | |
| C03        |  MERRA2        | reanalysis     | netCDF   | 1980-2025, global  |  [MERRA2](https://doi.org/10.5067/WWQSXQ8IVFW8) | unknown | - | [Katharina Turhal](k.turhal@fz-juelich.de) | |
| C03        |  Eddy Tracking Tool       | software     | python   | - |  FZJ, ICE-4, Jan Clemens | initial creation 2021-01-08 | 2024-08-06 | [Katharina Turhal](k.turhal@fz-juelich.de) | A modular toolkit to define, detect and track atmospheric structures (streamer, eddies, transport barriers) in reanalysis and model data. |
| C03        |  QBO Dataset   | data     | tab-serparated values (ascii)   | 1948-2023 |  [FU Berlin](https://www.geo.fu-berlin.de/en/met/ag/strat/produkte/qbo/index.html#references) | 2023-04-12 | NA | [Katharina Turhal](k.turhal@fz-juelich.de) |  |
| C03        |  PV tropopause | data     | netCDF   | 1980-2017, monthly data, isentropic levels | FZJ, project C03 | initial creation 2024-01-18, [zenodo](https://doi.org/10.5281/zenodo.10529153) | v1 | [Katharina Turhal](k.turhal@fz-juelich.de) | Associated with a [publication](https://doi.org/10.5194/acp-24-13653-2024)  |
| C04        |           |      |        |          |              |                    |         |         | |
| C05        | MLS | sat. data | netCDF | 2004-2020; 1hPa-316 hPa, 4.2° res. | provided by C03 (F. Plöger), [online](https://disc.gsfc.nasa.gov) | NA | v5 | [Frederik Harzer](frederik.harzer@physik.lmu.de) | Associated with [Harzer et al., 2023](https://doi.org/10.5194/acp-23-10661-2023)|
| C05        | ERA5 | reanalysis | netCDF | 1959-2022; 1hPa-1000 hPa, 1.5° res. | [CDS store](https://cds.climate.copernicus.eu) | NA | NA | [Frederik Harzer](frederik.harzer@physik.lmu.de) | Associated with [Harzer et al., 2023](https://doi.org/10.5194/acp-23-10661-2023)|
| C05        | ERA-Interim | reanalysis | netCDF | 1979-2016; 1hPa-1000 hPa, 0.7° res., zonal mean | [CDS store](https://cds.climate.copernicus.eu), NCAR data store | NA | NA | [Frederik Harzer](frederik.harzer@physik.lmu.de) | Associated with [Harzer et al., 2023](https://doi.org/10.5194/acp-23-10661-2023)|
| C06        |           |      |        |          |              |                    |         |         | |
| C07        |           |      |        |          |              |                    |         |         | |
|            |           |      |        |          |              |                    |         |         | |
| Z01        |  TPEx - Merged data set  | obs./mod. data   | netCDF  | 2024/06/10-2024/06/21 , TPex area | [zenodo](https://doi.org/10.5281/zenodo.15371527) | 2025/05/09 | v1  | [Hans-Christoph Lachnitt](hlachnit@uni-mainz.de) | |
| Z02        |           |      |        |          |              |                    |         |         | |
| Z03        |           |      |        |          |              |                    |         |         | |
