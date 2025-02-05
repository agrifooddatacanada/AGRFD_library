---
layout: default  
title: Feed Intake Carts 
parent: Ontario Dairy Research Centre 
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: feed_carts  
**Description**: Feed Intake from animals housed at the Tie Stall & Maternity. Feed is offered in the morning with a Super Data Ranger, which records the exact amount of feed dropped from equipment to the individual animal. Left-over feed (orts) is manually shoveled into the Orts Cart on the following morning before new feed is offered to the animal. Because of the way the scale on the Orts Cart is setup, orts are recorded as negative values, e.g., an orts value of -10.5 means the animal had 10.5 Kg of orts in front of her in the morning. Total intake is calculated only when both amounts are available. If there is no value for feed offered or orts, such data is missing.  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  

[Download Schema](Schema_Feed_Carts.zip)  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| date | Date | Date feed was offered (dropped) to the animal with the Super Data Ranger cart |
| date_orts | Date Orts | Date orts (left-over feed) was collected from the animal before more feed was offered (Kg) |
| feed_offered | Feed Offered | Amount of feed offered (dropped) to the animal (Kg) |
| feed_orts | Feed Orts | Amount of orts (left-over feed) (Kg) |
| total_intake | Total Intake | Total intake from one morning to another (Kg) |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | feed_carts | Feed Intake from animals housed at the Tie Stall & Maternity. Feed is offered in the morning with a Super Data Ranger, which records the exact amount of feed dropped from equipment to the individual animal. Left-over feed (orts) is manually shoveled into the Orts Cart on the following morning before new feed is offered to the animal. Because of the way the scale on the Orts Cart is setup, orts are recorded as negative values, e.g., an orts value of -10.5 means the animal had 10.5 Kg of orts in front of her in the morning. Total intake is calculated only when both amounts are available. If there is no value for feed offered or orts, such data is missing. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| date | false |  | DateTime | utf-8 |
| date_orts | false |  | DateTime | utf-8 |
| feed_offered | false |  | Numeric | utf-8 |
| feed_orts | false |  | Numeric | utf-8 |
| total_intake | false |  | Numeric | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID | Not a list |
| date | Date | Date feed was offered (dropped) to the animal with the Super Data Ranger cart | Not a list |
| date_orts | Date Orts | Date orts (left-over feed) was collected from the animal before more feed was offered (Kg) | Not a list |
| feed_offered | Feed Offered | Amount of feed offered (dropped) to the animal (Kg) | Not a list |
| feed_orts | Feed Orts | Amount of orts (left-over feed) (Kg) | Not a list |
| total_intake | Total Intake | Total intake from one morning to another (Kg) | Not a list |

## Schema SAIDs

**Capture base**: EQQPSXc5dN4nrINnlp9XBjnUoMUnK98PA5VMD-NGLEpY

| Layer | SAID |
| --- | --- |
| character_encoding | EMz_raOMAYNBl6bQsp9PVnnf6xmZZ5T-QStBx-YCqW64 |
| information (en) | EGlDA7TuMtlcsTh_Ttxo_md1AOxHZzvNYeaaJ32-j42o |
| label (en) | E-u2oMXHYaoxQaT_TZFToBZmhts9OlvzjX7kfCCXqpa8 |
| meta (en) | EtiNI40xEAVppKnp5_xNxxC01FqUt_clL_1UXI-HAKgg |

**Date created**: 2024-12-03 15:13:19

