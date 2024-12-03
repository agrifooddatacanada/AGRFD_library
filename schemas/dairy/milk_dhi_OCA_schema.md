---
layout: default  
title: Milk - DHI analysis
parent: Ontario Dairy Research Centre    
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: milk_dhi  
**Description**: Results from DHI analysis on test-day samples  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca 

[Download Schema](Schema_Milk_DHI.zip) 

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| date | Date | Milk sampling date |
| dim | Days in Milk | Number of days into current lactation at the time of the event. For dry cows, total days in most recent lactation including while dry. |
| ecm | Energy-corrected Milk | Energy-corrected milk (ECM) determines the amount of milk produced adjusted to 3.5% butterfat and 3.2% protein (in L) |
| lact_n | Lactation Number | Lactation number on the day of sampling |
| ls | Linear Score SCC | Linear score is a base 2 log transformation of SCC. The converted linear scores have a direct or straight-line relationship with milk yield. |
| milk | Milk Yield | Litres of milk produced on the day of sampling |
| milk_305 | Milk 305 | Projected milk yield for a 305-day lactation period |
| mun | Milk Urea Nitrogen | Milk urea nitrogen (MUN) in testday sample. The amount of MUN in the milk (in mg/dl). |
| pctf | Fat Percentage | Milkfat percentage of total milk weight in test day sample |
| pctp | Protein Percentage | Protein percentage of total milk weight in test day sample |
| pos | Barn Position | Barn position when sampled (innacurate - to be discontinued) |
| relv | Relative Milk 305 | The percentage of the test day milk sample's 305ME Milk value normalized to the Herd Average 305ME Milk for that testday. 100% if 305ME Milk result is exactly the herd average for 305ME milk. |
| scc | Somatic Cell Count | Somatic cell count in the test day sample (x1000 cells/mL). |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | milk_dhi | Results from DHI analysis on test-day samples |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| date | false |  | DateTime | utf-8 |
| dim | false |  | Numeric | utf-8 |
| ecm | false |  | Numeric | utf-8 |
| lact_n | false |  | Numeric | utf-8 |
| ls | false |  | Numeric | utf-8 |
| milk | false |  | Numeric | utf-8 |
| milk_305 | false |  | Numeric | utf-8 |
| mun | false |  | Numeric | utf-8 |
| pctf | false |  | Numeric | utf-8 |
| pctp | false |  | Numeric | utf-8 |
| pos | false |  | Numeric | utf-8 |
| relv | false |  | Numeric | utf-8 |
| scc | false |  | Numeric | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID | Not a list |
| date | Date | Milk sampling date | Not a list |
| dim | Days in Milk | Number of days into current lactation at the time of the event. For dry cows, total days in most recent lactation including while dry. | Not a list |
| ecm | Energy-corrected Milk | Energy-corrected milk (ECM) determines the amount of milk produced adjusted to 3.5% butterfat and 3.2% protein (in L) | Not a list |
| lact_n | Lactation Number | Lactation number on the day of sampling | Not a list |
| ls | Linear Score SCC | Linear score is a base 2 log transformation of SCC. The converted linear scores have a direct or straight-line relationship with milk yield. | Not a list |
| milk | Milk Yield | Litres of milk produced on the day of sampling | Not a list |
| milk_305 | Milk 305 | Projected milk yield for a 305-day lactation period | Not a list |
| mun | Milk Urea Nitrogen | Milk urea nitrogen (MUN) in testday sample. The amount of MUN in the milk (in mg/dl). | Not a list |
| pctf | Fat Percentage | Milkfat percentage of total milk weight in test day sample | Not a list |
| pctp | Protein Percentage | Protein percentage of total milk weight in test day sample | Not a list |
| pos | Barn Position | Barn position when sampled (innacurate - to be discontinued) | Not a list |
| relv | Relative Milk 305 | The percentage of the test day milk sample's 305ME Milk value normalized to the Herd Average 305ME Milk for that testday. 100% if 305ME Milk result is exactly the herd average for 305ME milk. | Not a list |
| scc | Somatic Cell Count | Somatic cell count in the test day sample (x1000 cells/mL). | Not a list |

## Schema SAIDs

**Capture base**: EO7a7u0Iy1PUWVSYtzUxh7G9bKwMEr_0OIFVqp-18gyU

| Layer | SAID |
| --- | --- |
| character_encoding | EW8L2uiJ5cYRCQ89gcZGc2K69HdNx12trVBEDHCVtK40 |
| information (en) | EdjaH2S1BILLcVBJoj1jcm27a2fxjKG8voECaObqkaPs |
| label (en) | EHVxsKfTwgGgJMIxwo061s-ZiFkiE6wWJiXEuHHR8V-8 |
| meta (en) | EtnjPCBjt9seUr7ujEX-peN0AHJC6X5OkmUPhk0ntwXc |

**Date created**: 2024-12-03 15:14:30

