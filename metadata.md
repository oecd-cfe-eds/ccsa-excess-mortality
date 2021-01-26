# Metadata

*Table of Contents*

- [OECD Regional Typology and Territorial Grid](#oecd-regional-typology-and-territorial-grid)
- [Data sources](#data-sources)
  - [Australia](#australia)
  - [Canada](#canada)
  - [Chile](#chile)
  - [Colombia](#colombia)
  - [Eurostat](#eurostat)
  - [Germany](#germany)
  - [Israel](#israel)
  - [Japan](#japan)
  - [Korea](#korea)
  - [Mexico](#mexico)
  - [New Zealand](#new-zealand)
  - [United States](#united-states)

***

## OECD Regional Typology and Territorial Grid

Subnational regions within the 37 OECD countries are classified into two 
territorial levels reflecting the administrative organisation of countries: 
large regions (territorial level 2 or TL2) composed by 427 regions, and small 
regions (TL3) composed by 2 290 regions. Small regions can be further classified 
into three groups based on their level of access to metropolitan areas 
(i.e. dense and highly populated functional urban areas of at least 250 000 
inhabitants): Metropolitan regions, Regions close to a metropolitan area, and 
Regions far from a metropolitan area (composed of Regions with/near a small-medium 
city, and Remote regions). For more details, see Fadic, M. et al. 2019.

Maps of the territorial levels of OECD countries as of March 2020 
are depicted in the [OECD Territorial Grid](http://www.oecd.org/regional/regional-policy/42392313.pdf).

> OECD (2020), OECD Regions and Cities at a Glance 2020, OECD Publishing,
> <https://doi.org/10.1787/959d5ba0-en>. 
>
> Fadic, M. et al. (2019), "Classifying
> small (TL3) regions based on metropolitan population, low density and
> remoteness", OECD Regional Development Working Papers, No. 2019/06, OECD
> Publishing, <https://doi.org/10.1787/b902cc00-en>.

## Data sources

### Australia

Monthly death counts are aggregated from weekly counts. We report the same numbers for the *Australian Capital Territory* and *Northern Territory* because the Australian Bureau of Statistics lumps together both regions. 

- **Latest release:** December 21, 2020.
- **Definition of deaths:** Doctor-certified deaths, on the date in which the death occurred, by place of death.


| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Weekly    | TL1, TL2  | ABS - [3303.0.55.004 - Provisional Mortality Statistics, Jan - Apr 2020](https://www.abs.gov.au/AUSSTATS/abs@.nsf/mf/3303.0.55.004) |

### Canada

Monthly death counts are aggregated from weekly counts.

- **Latest update:** January 11, 2020.
- **Definition of deaths:** The geographic distribution of deaths is based on the deceased's place of death and for residents of Canada only. The data for the 2018 to 2020 reference years are provisional.

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Weekly    | TL2       | Statistics Canada - [Table 13-10-0768-01](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1310076801) |

### Chile

Mortality data is treated and collected by the [Ministerio de Ciencia, Tecnología, Conocimiento e Innovación](http://www.minciencia.gob.cl/covid19) based on deaths reported to the National Registry office.

Monthly death counts are aggregated from weekly counts. Aggregation to the TL3, TL2 and TL1 level is based on death counts reported at the *comuna* level.

Missing values for the following regions were imputed by zero: Parinacota, Chañaral, Capitán Prat, General Carrera, Antártica Chilena, Tierra del Fuego, Tamarugal, Isla de Pascua.

- **Latest update:** December 15, 2020.
- **Definition of deaths:** By place of death. The date of death corresponds to the date the death was reported to the registry's office.


| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Daily     | TL2, TL3  | Ministerio de Ciencia, Tecnología, Conocimiento e Innovación - [Data product #32](https://github.com/MinCiencia/Datos-COVID19/tree/master/output/producto32) |

### Colombia

- **Latest data release:** December 23, 2020.


| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Weekly    | TL1, TL2  | DANE - [Informe de seguimiento - Defunciones por COVID-19](https://www.dane.gov.co/index.php/estadisticas-por-tema/demografia-y-poblacion/informe-de-seguimiento-defunciones-por-covid-19) |

### Eurostat

- **Latest update:** January 4, 2021.

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Weekly    | TL1, TL2, TL3  | Eurostat - [Deaths by week, sex, 5-year age group and NUTS 3 region](https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=demo_r_mweek3&lang=en) |

### Germany

Monthly death counts come from the publication [Sterbefälle - Fallzahlen nach Tagen, Wochen, Monaten, Altersgruppen und Bundesländern für Deutschland 2016-2020](https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Bevoelkerung/Sterbefaelle-Lebenserwartung/Tabellen/sonderauswertung-sterbefaelle.html).

- **Definition of deaths:** By place of residence.
- **Latest data release:** December 30, 2020.
- **Notes:** The influenza epidemic was particularly severe in Germany in March 2018.

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Monthly   | TL1, TL2  | DESTATIS |


### Israel

Data comes from the September 2020 Statistical Monthly Release of the Central Bureau of Statistics. 

- **Latest data release:** December 16, 2020.

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Daily   | TL2  | Central Bureau of Statistics - [Deaths of Israeli Residents By Day of Death, District and Population Group, 2020](https://www.cbs.gov.il/he/subjects/Pages/%D7%AA%D7%9E%D7%95%D7%AA%D7%94-%D7%95%D7%AA%D7%95%D7%97%D7%9C%D7%AA-%D7%97%D7%99%D7%99%D7%9D.aspx) |

### Japan

- **Latest update:** January 5, 2021.

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts (until 2020-07) | Monthly | TL1, TL3 | e-Stat Portal - [月報](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00450011&tstat=000001028897&cycle=1&tclass1=000001053058&tclass2=000001053060&cycle_facet=tclass1%3Acycle) |
| Death counts (after 2020-07) | Monthly | TL1, TL3 | e-Stat Portal - [速報](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00450011&tstat=000001028897&cycle=1&tclass1=000001053058&tclass2=000001053059&cycle_facet=tclass1%3Acycle) |

### Korea

- **Latest update:** January 5, 2021.


| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Monthly   | TL1, TL3 | KOSIS - [Vital statistics](http://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1B8000G&conn_path=I2&language=en) |

### Mexico

Monthly death counts are aggregated from individual-level data. Numbers at the TL1 level correspond to the sum of deaths across 32 TL2 regions.

- **Latest update:** January 7, 2021
- **Definition of deaths:** By place of occurrence, at the date of death. 

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts (2020)      | Daily | TL1, TL2 | [Bases de datos del boletín estadístico sobre el exceso de mortalidad en México](https://www.datos.gob.mx/busca/dataset/bases-de-datos-del-boletin-estadistico-sobre-el-exceso-de-mortalidad-en-mexico)|
| Death counts (2015-2019) | Daily | TL1, TL2 | [INEGI - Defunciones registradas (Microdatos)](https://www.inegi.org.mx/programas/mortalidad/?ps=microdatos) |

### New Zealand

Monthly death counts correspond to quarterly death counts divided by three.

- **Latest data release:** 17 November 2020
- **Definition of deaths:** Deaths data are based on deaths registered in New Zealand to people resident in New Zealand by date of registration.

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts | Quarterly | TL1, TL2 | Stats NZ - [Table VSD016AA](http://archive.stats.govt.nz/infoshare/default.aspx) |

### United States

Monthly death counts are aggregated from weekly counts, and national death counts are aggregated from TL2 regions.

- **Definition of deaths:** By place of occurrence.

| Variable     | Frequency | Geography | Source |
|--------------|-----------|-----------|--------|
| Death counts (2014-2018) | Weekly    | TL1, TL2 | [CDC](https://data.cdc.gov/NCHS/Weekly-Counts-of-Deaths-by-State-and-Select-Causes/3yf8-kanr) |
| Death counts (2019-2020) | Weekly    | TL1, TL2 | [CDC](https://data.cdc.gov/NCHS/Weekly-Counts-of-Deaths-by-State-and-Select-Causes/muzy-jte6) |
