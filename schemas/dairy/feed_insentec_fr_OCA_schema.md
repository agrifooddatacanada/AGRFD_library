---
layout: default  
title: Feed Insentec: Fixed Records
parent: Ontario Dairy Research Centre
---

## Schema information

**Name**: feed_insentec_fr  
**Description**: Insentec data from VR files with end weight and intake fixed. Assumption: the start weight of the following visit is more accurate than the end weight of the current visit, since the scale on the bin had more time to get a more stabilized weight before the next cow's visit. Fixing strategy: If start weight of following visit is equal (cow didn't eat) or smaller than the current visit's start weight (cow ate), and the following visit's start weight is different than the current visit's end weight, then the current visit's end weight is replaced with the start weight of the following visit. These conditions are applied with data grouped by date and bin, and sorted ascending by start time. Limitation: because data is grouped by date, if the last visit of a day registered an incorrect weight to a bin, it will not be corrected with the first visit of the following day of such bin. Additionally, if the start weight of the following visit is greater than the start weight of the current visit, then nothing is done, since supplement/more feed could have been added to the bin between visits or the scale was really broken. Further inspection to the data is recommended.  
**Classification**: RDF402 

[Download Schema](Schema_Feed_Insenetc_FR.zip) 

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| bin_id | Bin ID | Feed bin ID |
| date | Date | Date the animal's RFID was read at the beginning of visit |
| diet | Diet | Diet inside of the feed bin. Animal-specific diets are named after the respective animal's number |
| duraction_sec | Duration in Seconds | Duration of the visit |
| end_time | End TIme | Time the animal's RFID was read at the end of visit, without time zone. |
| end_weight_kg | End Weight in Kilograms | Weight of the feed bin at the end of visit |
| fixed | Fixed | True if end_weight_kg and intake_kg were fixed to account for predictable negative intake_kg values. False otherwise |
| intake_kg | Intake | Difference between end_weight and start_weight |
| start_time | Start Time | Time the animal's RFID was read at the beginning of visit, without time zone. |
| start_weight_kg | Start Weight in Kilograms | Weight of the feed bin at the beginning of visit |
| transponder_id | Transponder ID | RFID from animal tag |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | feed_insentec_fr | Insentec data from VR files with end weight and intake fixed. Assumption: the start weight of the following visit is more accurate than the end weight of the current visit, since the scale on the bin had more time to get a more stabilized weight before the next cow's visit. Fixing strategy: If start weight of following visit is equal (cow didn't eat) or smaller than the current visit's start weight (cow ate), and the following visit's start weight is different than the current visit's end weight, then the current visit's end weight is replaced with the start weight of the following visit. These conditions are applied with data grouped by date and bin, and sorted ascending by start time. Limitation: because data is grouped by date, if the last visit of a day registered an incorrect weight to a bin, it will not be corrected with the first visit of the following day of such bin. Additionally, if the start weight of the following visit is greater than the start weight of the current visit, then nothing is done, since supplement/more feed could have been added to the bin between visits or the scale was really broken. Further inspection to the data is recommended. |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | Animal ID | Farm-level unique animal ID | Not a list | utf-8 |
| bin_id | false |  | Numeric | Bin ID | Feed bin ID | Not a list | utf-8 |
| date | false |  | DateTime | Date | Date the animal's RFID was read at the beginning of visit | Not a list | utf-8 |
| diet | false |  | Text | Diet | Diet inside of the feed bin. Animal-specific diets are named after the respective animal's number | Not a list | utf-8 |
| duraction_sec | false |  | Numeric | Duration in Seconds | Duration of the visit | Not a list | utf-8 |
| end_time | false |  | DateTime | End TIme | Time the animal's RFID was read at the end of visit, without time zone. | Not a list | utf-8 |
| end_weight_kg | false |  | Numeric | End Weight in Kilograms | Weight of the feed bin at the end of visit | Not a list | utf-8 |
| fixed | false |  | Boolean | Fixed | True if end_weight_kg and intake_kg were fixed to account for predictable negative intake_kg values. False otherwise | Not a list | utf-8 |
| intake_kg | false |  | Numeric | Intake | Difference between end_weight and start_weight | Not a list | utf-8 |
| start_time | false |  | DateTime | Start Time | Time the animal's RFID was read at the beginning of visit, without time zone. | Not a list | utf-8 |
| start_weight_kg | false |  | Numeric | Start Weight in Kilograms | Weight of the feed bin at the beginning of visit | Not a list | utf-8 |
| transponder_id | false |  | Numeric | Transponder ID | RFID from animal tag | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: Eb9qaLLeZLyqoN2va-uN6adcgtiaYcilXBcYgShMQyhA

| Layer | SAID |
| --- | --- |
| character_encoding | EzWuNWsJdVY1g3bPAqVOVzjmRhFiwxXZr7_aT4ql3gcU |
| information (en) | Esn74OXqTYisfVK9s9xFwxtbgDpxp9pKRKtofTMH6sko |
| label (en) | ESAPLM8LF6Zx5tb28SGErahDwSeYP_dSGwrKJGUqQMUg |
| meta (en) | EdP4YhhujElWov33PyyjX6jYPKoFPDQ8nmtLIRQpUDbc |
