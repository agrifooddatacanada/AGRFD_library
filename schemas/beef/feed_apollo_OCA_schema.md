---
layout: default  
title: feed_apollo  
---

## Schema information

**Name**: feed_apollo  
**Description**: Raw data from Insentec's daily VR files. Every time an animal visits an Insentec bin, a record is created. Therefore, each file has all visits made by all animals to all bins on a given day. These files are appended to this table every day.  
**Classification**: RDF402  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| apollo_id | Apollo ID | Animal ID used on Apollo |
| bin_id | Bin ID | Feed bin ID |
| date | Date | Date the animal's RFID was read at the beginning of visit |
| diet | Diet | Diet inside of the feed bin. Animal-specific diets are named after the respective animal's number |
| duration_sec | Duration in Seconds | Duration of the visit |
| end_time | End Time | Time the animal's RFID was read at the end of visit |
| end_weight_kg | End Weight in Kilograms | Weight of the feed bin at the end of visit |
| intake | Intake in Kilograms | Difference between end_weight and start_weight |
| start_time | Start Time | Time the animal's RFID was read at the beginning of visit |
| start_weight_kg | Start Weight in Kilograms | Weight of the feed bin at the beginning of visit |
| transponder_id | Transponder ID | RFID from animal tag |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | feed_apollo | Raw data from Insentec's daily VR files. Every time an animal visits an Insentec bin, a record is created. Therefore, each file has all visits made by all animals to all bins on a given day. These files are appended to this table every day. |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| apollo_id | false |  | Numeric | Apollo ID | Animal ID used on Apollo | Not a list | utf-8 |
| bin_id | false |  | Numeric | Bin ID | Feed bin ID | Not a list | utf-8 |
| date | false |  | DateTime | Date | Date the animal's RFID was read at the beginning of visit | Not a list | utf-8 |
| diet | false |  | Text | Diet | Diet inside of the feed bin. Animal-specific diets are named after the respective animal's number | Not a list | utf-8 |
| duration_sec | false |  | DateTime | Duration in Seconds | Duration of the visit | Not a list | utf-8 |
| end_time | false |  | DateTime | End Time | Time the animal's RFID was read at the end of visit | Not a list | utf-8 |
| end_weight_kg | false |  | Numeric | End Weight in Kilograms | Weight of the feed bin at the end of visit | Not a list | utf-8 |
| intake | false |  | Numeric | Intake in Kilograms | Difference between end_weight and start_weight | Not a list | utf-8 |
| start_time | false |  | DateTime | Start Time | Time the animal's RFID was read at the beginning of visit | Not a list | utf-8 |
| start_weight_kg | false |  | Numeric | Start Weight in Kilograms | Weight of the feed bin at the beginning of visit | Not a list | utf-8 |
| transponder_id | false |  | Numeric | Transponder ID | RFID from animal tag | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: EVzAk_za6zZ0H2syBQ7GA8dvEmb-4NxbzeGIEhkCiRj8

| Layer | SAID |
| --- | --- |
| character_encoding | E9b4OOVEGfJsu0XU2wW4vfo1G7OQCpHi4aHlEsEX9u_I |
| information (en) | EUrBxJgEpbxKuBtFfYKtvkfu0_3FrOCmmIfkjiy3p2WM |
| label (en) | EpLYvNpnmzh_SxS4bAo9MZEuE9nlW_v0op-yf9MZs3jg |
| meta (en) | EVQz6pLJJMDj-g_T7ggxx4H0EqSozR18M8EflmnG2wQ4 |

**Date created**: 2024-11-21 10:22:28

