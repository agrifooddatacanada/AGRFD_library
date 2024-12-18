---
layout: default  
title: Conformation BCS
parent: Ontario Dairy Research Centre   
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: conformation_bcs  
**Description**: Body Condition Score (BCS) collected from BCS cameras places at the exit of the Milking Parlour & at the exit of the Voluntary Milking System (VMS). Data collection happens after milkings (Parlour and VMS), after foot bath (Monday, Wednesday, and Friday afternoons) or at another time when animals are individually brought to the walk-over scale.  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca 

[Download Schema](Schema_BCS.zip) 


## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| collection_moment | Collection Moment | Moment the score was measured (During milking time, foot bath or other time) |
| date | Date | Date of Event |
| raw_bcs | Raw Body Condition Score | Body Condition Score (BCS) estimated through a BCS 3D camera. Score goes from 1 to 5. |
| source | Source | Source/Location of the BCS camera (Parlour, Robot, or Heifer barn) |
| source_id | Source ID | Source ID. 1 = Parlour, 2 = Foot Bath or Other, 3 = Voluntary Milking System |
| time | Time | Time the animal's RFID was read when passing through the BCS camera, without time zone. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | conformation_bcs | Body Condition Score (BCS) collected from BCS cameras places at the exit of the Milking Parlour & at the exit of the Voluntary Milking System (VMS). Data collection happens after milkings (Parlour and VMS), after foot bath (Monday, Wednesday, and Friday afternoons) or at another time when animals are individually brought to the walk-over scale. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| collection_moment | false |  | Text | utf-8 |
| date | false |  | DateTime | utf-8 |
| raw_bcs | false |  | Numeric | utf-8 |
| source | false |  | Text | utf-8 |
| source_id | false |  | Numeric | utf-8 |
| time | false |  | DateTime | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID | Not a list |
| collection_moment | Collection Moment | Moment the score was measured (During milking time, foot bath or other time) | Not a list |
| date | Date | Date of Event | Not a list |
| raw_bcs | Raw Body Condition Score | Body Condition Score (BCS) estimated through a BCS 3D camera. Score goes from 1 to 5. | Not a list |
| source | Source | Source/Location of the BCS camera (Parlour, Robot, or Heifer barn) | Not a list |
| source_id | Source ID | Source ID. 1 = Parlour, 2 = Foot Bath or Other, 3 = Voluntary Milking System | Not a list |
| time | Time | Time the animal's RFID was read when passing through the BCS camera, without time zone. | Not a list |

## Schema SAIDs

**Capture base**: EOx--Q96bbiBLWsIfe1ymwyBUN7jQxL9NoA00RiWTKhw

| Layer | SAID |
| --- | --- |
| character_encoding | E5ofrWN2I8UsVVjIHjxkuE9xfejd4UST5nbgJph6nsDU |
| information (en) | EFjKI1v9jN6VWA980PaPYPFMUJyIbDSyxNDK07QgHpvw |
| label (en) | E-cDyiqPm6R6JPINcFJlV236eqRzBSnAe6_KKwfQMcE4 |
| meta (en) | EuZEj_hrm3FMswfFgegdG_Fd0_ObI53_73ZhB77jJK5U |

**Date created**: 2024-12-03 15:12:26

