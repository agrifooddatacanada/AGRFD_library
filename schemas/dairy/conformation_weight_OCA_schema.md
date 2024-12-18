---
layout: default  
title: Conformation Weight
parent: Ontario Dairy Research Centre   
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: conformation_weight  
**Description**: Body Weight collected on a walk-over scale placed at the exit of the Milking Parlour. Data collection normally happens after milkings (AM or PM), after foot bath (Monday, Wednesday, and Friday afternoons) or at another time when animals are individually brought to the walk-over scale.  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  

[Download Schema](Schema_Conformation_Weight.zip)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id |  | Farm-level unique animal ID |
| collection_moment |  | Moment the body weight was measured (Heifer Scale, during milking time or another time between 8AM and 4PM, including foot bath) |
| date |  | Date the animal's RFID was read when passing through the BCS camera |
| dim |  | Number of days in milk when measure was taken |
| lact_n |  | Lactation number when measure was taken |
| session_n |  | Session number. 1 = AM, 2 = PM |
| source |  | Source/Location of the walk-over full-body scale (Parlour or Heifer Barn) |
| source_id |  | Source ID. 1 = Parlour, 2 = Foot bath or other, 3 = Heifer barn |
| time |  | Time the animal's RFID was read when passing through the BCS camera |
| weight |  | Weight of the animal measured while it walks over a the scale |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | conformation_weight | Body Weight collected on a walk-over scale placed at the exit of the Milking Parlour. Data collection normally happens after milkings (AM or PM), after foot bath (Monday, Wednesday, and Friday afternoons) or at another time when animals are individually brought to the walk-over scale. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| collection_moment | false |  | Text | utf-8 |
| date | false |  | DateTime | utf-8 |
| dim | false |  | Numeric | utf-8 |
| lact_n | false |  | Numeric | utf-8 |
| session_n | false |  | Numeric | utf-8 |
| source | false |  | Text | utf-8 |
| source_id | false |  | Numeric | utf-8 |
| time | false |  | DateTime | utf-8 |
| weight | false |  | Numeric | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id |  | Farm-level unique animal ID | Not a list |
| collection_moment |  | Moment the body weight was measured (Heifer Scale, during milking time or another time between 8AM and 4PM, including foot bath) | Not a list |
| date |  | Date the animal's RFID was read when passing through the BCS camera | Not a list |
| dim |  | Number of days in milk when measure was taken | Not a list |
| lact_n |  | Lactation number when measure was taken | Not a list |
| session_n |  | Session number. 1 = AM, 2 = PM | Not a list |
| source |  | Source/Location of the walk-over full-body scale (Parlour or Heifer Barn) | Not a list |
| source_id |  | Source ID. 1 = Parlour, 2 = Foot bath or other, 3 = Heifer barn | Not a list |
| time |  | Time the animal's RFID was read when passing through the BCS camera | Not a list |
| weight |  | Weight of the animal measured while it walks over a the scale | Not a list |

## Schema SAIDs

**Capture base**: EOyAi0wGIt_pmJUhTHVi2e9fbEZeJRezPpnTv44MApuM

| Layer | SAID |
| --- | --- |
| character_encoding | EMMZFSPWodCmJFnFWNdf3MPI-yAC3oGoYj_3BxefNNWY |
| information (en) | EyFCN4d86e9qqC1R6wbMKADkJWu2lv-E9ae9-RvJhTmM |
| label (en) | EmasdAVplYtpbTZ039IJH1qTbh4RCd3SkoB0-IZp_zWQ |
| meta (en) | EDuK0y5mPbqNcpLp35Vm7zSQuF4rPOUexdNt-JonlX9Y |

**Date created**: 2024-12-03 15:12:42

