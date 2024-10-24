---
layout: default  
title: Feed Insentec: Raw Data VR  
parent: Ontario Dairy Research Centre 
---

## Schema information

**Name**: feed_insentec_vr  
**Description**: Raw data from Insentec's daily VR files. Every time a cow or heifer visits an Insentec bin from pens 405 to 408 or 301 to 303, a record is created. Therefore, each file has all visits made by all animals to all bins on a given day. These files are appended to this table every day.  
**Classification**: RDF402 

[Download Schema](Schema_Feed_Insentec_VR.zip) 

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
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
| English | feed_insentec_vr | Raw data from Insentec's daily VR files. Every time a cow or heifer visits an Insentec bin from pens 405 to 408 or 301 to 303, a record is created. Therefore, each file has all visits made by all animals to all bins on a given day. These files are appended to this table every day. |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | Animal ID | Farm-level unique animal ID | Not a list | utf-8 |
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

**Capture base**: EY2MstiQAo9N8bZrz8npN_zA8F6HGpTkFmFshS1ysNfM

| Layer | SAID |
| --- | --- |
| character_encoding | EXWBr-JHBxqtGGRXgutiYmnSFkCXM6nvgblbq-JxnYbc |
| information (en) | E5sppV_lbhyLlPSaAjLVTfia7gikuV_zW5FfOR66ewBQ |
| label (en) | E9iJtJ69QSIO5KsH3Oi08Ovy3ozak8coq879cqUneDTg |
| meta (en) | ETjVR7b3OyOhySAc4fnOQr7HP5MyI-buGlBUvWTJaMIw |
