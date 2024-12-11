---
layout: default  
title: animal_ebvs  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: animal_ebvs  
**Description**: This table contains Estimated Breeding Values (EBVs) extracted from DairyComp. These results are released directly by Lactanet on the first Wednesday of each month, coinciding with the herd's DHI test results. Official results are provided for the months of April, August, and December, while results from other months are considered unofficial. If animals have been genotyped, the results will be genomic EBVs. To prevent data duplication, a record for any given animal is only added to the database if at least one EBV has changed from the previous month, or if new results are available.  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| date | Date | Date results became available on DairyComp |
| gbcs | Body Condition Score |  |
| gbeta | Beta Casein |  |
| gbmr | Body Maintenance Requirements |  |
| gconf | Conformation |  |
| gdeas | Daughter Calving Ease |  |
| gdf | Daughter Fertility |  |
| gease | Calving Ease |  |
| genom | Genomic | Indicates if animal if results are genomic EBVs (G) or not (null). |
| gfat | Fat Yield |  |
| gfe | Feed Efficiency |  |
| gfl | Feet and Legs |  |
| gfpct | Fat Percentage |  |
| ggpct | Protein Percentage |  |
| ghh | Hoof Health |  |
| ghl | Herd Life |  |
| ginb | Inbreeding Percentage |  |
| gkapa | Kappa Casein |  |
| gloco | Locomotion |  |
| glpi | Lifetime Performance Index (LPI) |  |
| gmamm | Mammary System |  |
| gmdr | Metabolic Disease Reistance |  |
| gme | Methane Efficiency |  |
| gmilk | Milk Yield |  |
| gmr | Mastitis Resistance |  |
| gpers | Lactation Persistance |  |
| gpoll | Polled Gene |  |
| gprodollar | Prodollar |  |
| gprot | Protein Yield |  |
| grump | Rump |  |
| gscs | Somatic Cell Score |  |
| gteat | Teat Length |  |
| gtmp | Milking Temperament |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | animal_ebvs | This table contains Estimated Breeding Values (EBVs) extracted from DairyComp. These results are released directly by Lactanet on the first Wednesday of each month, coinciding with the herd's DHI test results. Official results are provided for the months of April, August, and December, while results from other months are considered unofficial. If animals have been genotyped, the results will be genomic EBVs. To prevent data duplication, a record for any given animal is only added to the database if at least one EBV has changed from the previous month, or if new results are available. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| date | false |  | DateTime | utf-8 |
| gbcs | false |  | Numeric | utf-8 |
| gbeta | false |  | Text | utf-8 |
| gbmr | false |  | Numeric | utf-8 |
| gconf | false |  | Numeric | utf-8 |
| gdeas | false |  | Numeric | utf-8 |
| gdf | false |  | Numeric | utf-8 |
| gease | false |  | Numeric | utf-8 |
| genom | false |  | Text | utf-8 |
| gfat | false |  | Numeric | utf-8 |
| gfe | false |  | Numeric | utf-8 |
| gfl | false |  | Numeric | utf-8 |
| gfpct | false |  | Numeric | utf-8 |
| ggpct | false |  | Numeric | utf-8 |
| ghh | false |  | Numeric | utf-8 |
| ghl | false |  | Numeric | utf-8 |
| ginb | false |  | Numeric | utf-8 |
| gkapa | false |  | Text | utf-8 |
| gloco | false |  | Numeric | utf-8 |
| glpi | false |  | Numeric | utf-8 |
| gmamm | false |  | Numeric | utf-8 |
| gmdr | false |  | Numeric | utf-8 |
| gme | false |  | Numeric | utf-8 |
| gmilk | false |  | Numeric | utf-8 |
| gmr | false |  | Numeric | utf-8 |
| gpers | false |  | Numeric | utf-8 |
| gpoll | false |  | Text | utf-8 |
| gprodollar | false |  | Numeric | utf-8 |
| gprot | false |  | Numeric | utf-8 |
| grump | false |  | Numeric | utf-8 |
| gscs | false |  | Numeric | utf-8 |
| gteat | false |  | Text | utf-8 |
| gtmp | false |  | Numeric | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID | Not a list |
| date | Date | Date results became available on DairyComp | Not a list |
| gbcs | Body Condition Score |  | Not a list |
| gbeta | Beta Casein |  | Not a list |
| gbmr | Body Maintenance Requirements |  | Not a list |
| gconf | Conformation |  | Not a list |
| gdeas | Daughter Calving Ease |  | Not a list |
| gdf | Daughter Fertility |  | Not a list |
| gease | Calving Ease |  | Not a list |
| genom | Genomic | Indicates if animal if results are genomic EBVs (G) or not (null). | Not a list |
| gfat | Fat Yield |  | Not a list |
| gfe | Feed Efficiency |  | Not a list |
| gfl | Feet and Legs |  | Not a list |
| gfpct | Fat Percentage |  | Not a list |
| ggpct | Protein Percentage |  | Not a list |
| ghh | Hoof Health |  | Not a list |
| ghl | Herd Life |  | Not a list |
| ginb | Inbreeding Percentage |  | Not a list |
| gkapa | Kappa Casein |  | Not a list |
| gloco | Locomotion |  | Not a list |
| glpi | Lifetime Performance Index (LPI) |  | Not a list |
| gmamm | Mammary System |  | Not a list |
| gmdr | Metabolic Disease Reistance |  | Not a list |
| gme | Methane Efficiency |  | Not a list |
| gmilk | Milk Yield |  | Not a list |
| gmr | Mastitis Resistance |  | Not a list |
| gpers | Lactation Persistance |  | Not a list |
| gpoll | Polled Gene |  | Not a list |
| gprodollar | Prodollar |  | Not a list |
| gprot | Protein Yield |  | Not a list |
| grump | Rump |  | Not a list |
| gscs | Somatic Cell Score |  | Not a list |
| gteat | Teat Length |  | Not a list |
| gtmp | Milking Temperament |  | Not a list |

## Schema SAIDs

**Capture base**: E0zwqZaZZmdighLXrwN46EijpNjNzJW_2HdNjWWl3L_A

| Layer | SAID |
| --- | --- |
| character_encoding | E5P-sbC8qQQb_PH0dgl4oz9m_Aq3TXdmtujEAtiLz7IE |
| information (en) | Ey9So9Xuo962b8NaRFCRAUXMpoXBP4sHrq4-iTI1qoZo |
| label (en) | EYjVR_Mo_M07I92bFqPM0hMYU-zWvvzoElW6cllBoTCM |
| meta (en) | E0dx4engXDi-TkLfN_q5WrRs-AFWfKhY4hH8kZvi4RPw |

**Date created**: 2024-12-11 09:45:19

