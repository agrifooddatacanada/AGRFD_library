---
layout: default  
title: Animal Events - Health 
parent: Ontario Dairy Research Centre  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Animal Events - Health  
**Description**: Records of health events entered on DairyComp  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  

[Download Schema](Schema_Animal_Events_Health.zip)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| breeding_code | Breeding Code | Breeding code |
| date | Date | Date of event |
| dim | Days in Milk | If heifer (lact_n = 0), age in days at time of event. If cow (lact_n > 0), days in milk at time of event. |
| event | Event | Event |
| lactation_n | Lactation Number | Lactation number at time of event |
| protocol | Protocol | Protocol used |
| remark | Remark | Event remark |
| remark_code | Remark Code | Remark code |
| technician_code | Technician Code | Technician code |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | animal_events_health | Records of health events entered on DairyComp |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| breeding_code | false |  | Text | utf-8 |
| date | false |  | DateTime | utf-8 |
| dim | false |  | Numeric | utf-8 |
| event | false |  | Text | utf-8 |
| lactation_n | false |  | Numeric | utf-8 |
| protocol | false |  | Text | utf-8 |
| remark | false |  | Text | utf-8 |
| remark_code | false |  | Text | utf-8 |
| technician_code | false |  | Text | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID | Not a list |
| breeding_code | Breeding Code | Breeding code | Not a list |
| date | Date | Date of event | Not a list |
| dim | Days in Milk | If heifer (lact_n = 0), age in days at time of event. If cow (lact_n > 0), days in milk at time of event. | Not a list |
| event | Event | Event | Not a list |
| lactation_n | Lactation Number | Lactation number at time of event | Not a list |
| protocol | Protocol | Protocol used | Not a list |
| remark | Remark | Event remark | Not a list |
| remark_code | Remark Code | Remark code | Not a list |
| technician_code | Technician Code | Technician code | Not a list |

## Schema SAIDs

**Capture base**: ExN2VXEKRY81jn4fxUZxHALuF1lVHF4U_ex06gZEfOsk

| Layer | SAID |
| --- | --- |
| character_encoding | ErARx7aM_TzSas0X5SSckVlDoN0LS79ba_v8yQZDmUR0 |
| information (en) | EEDseQu7q7_0nLMVMW_sd4FobMsdsk0MPkFDdbUCwhxM |
| label (en) | EqiAfF7_l1050a4mF_elXyseNFPbwQKj-a-vmRbkXVgs |
| meta (en) | EotMSPSYzu2MBujxeogtmuGTGFfWia6k38YM8IbK22h8 |

**Date created**: 2024-12-03 15:10:25

