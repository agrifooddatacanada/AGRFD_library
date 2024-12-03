---
layout: default  
title: Animal Events - Preventive
parent: Ontario Dairy Research Centre   
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: animal_events_preventive  
**Description**: Records of preventive treatments entered on DairyComp.  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca 

[Download Schema](Schema_Animal_Events_Preventive.zip) 

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id |  | Farm-level unique animal ID |
| breeding_code |  | Breeding code |
| date |  | Date of event |
| dim |  | If heifer (lact_n = 0), age in days at time of event. If cow (lact_n > 0), days in milk at time of event. |
| event |  | Event |
| lact_n |  | Lactation number at time of event |
| protocol |  | Protocol used |
| remark |  | Event remark |
| remark_code |  | Remark code |
| technician_code |  | Technician code |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | animal_events_preventive | Records of preventive treatments entered on DairyComp. |

## Selection lists

### English

#### remark_code entry codes

| Entry code | Label |
| --- | --- |
| 001 | Red |
| 002 | Green |
| 003 | Blue |
| 004 | Yellow |
| 005 | Orange |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| breeding_code | false |  | Text | utf-8 |
| date | false |  | DateTime | utf-8 |
| dim | false |  | Numeric | utf-8 |
| event | false |  | Text | utf-8 |
| lact_n | false |  | Numeric | utf-8 |
| protocol | false |  | Text | utf-8 |
| remark | false |  | Text | utf-8 |
| remark_code | false |  | Text | utf-8 |
| technician_code | false |  | Text | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id |  | Farm-level unique animal ID | Not a list |
| breeding_code |  | Breeding code | Not a list |
| date |  | Date of event | Not a list |
| dim |  | If heifer (lact_n = 0), age in days at time of event. If cow (lact_n > 0), days in milk at time of event. | Not a list |
| event |  | Event | Not a list |
| lact_n |  | Lactation number at time of event | Not a list |
| protocol |  | Protocol used | Not a list |
| remark |  | Event remark | Not a list |
| remark_code |  | Remark code | Red, Green, Blue, Yellow, Orange |
| technician_code |  | Technician code | Not a list |

## Schema SAIDs

**Capture base**: EETYxTE5ixqA21jluYQqBZgulf7klmvLzGYoTaK7x9eM

| Layer | SAID |
| --- | --- |
| character_encoding | E_2vmowu4lyrfMlJkYueNnQLntVNw2dd0UPMMQIIuVA8 |
| entry (en) | ELdvspsFwJDhOiMvYFin0ZCnDeje0a_vlpURn24Fo_B4 |
| entry_code | E8dbCJqjA5en4dufLqmUbWdvivtX5Pr7Mts80RQ5RXWo |
| information (en) | ElzTTCPQ6d2EkyEzJeOcTERDMNKmmcuQYNPn18vDxe0U |
| label (en) | E1hYRKtQMetGXA0NgYW8pAiF7kA6T4U5gCaz-9efl0i8 |
| meta (en) | ExSyexfTilGyd0k6UfJrENwERLvlnn7FJRDgk4heM_ts |

**Date created**: 2024-12-03 15:11:15

