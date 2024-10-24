---
layout: default  
title: Milk Voluntary Milking System(VMS) Action 
parent: Ontario Dairy Research Centre  
---

## Schema information

**Name**: milk_vms_action  
**Description**: Action taken by the Voluntary Milking System (VMS) when cow enters the VMS, either to accept or reject the cow for milking, or to release cow unmilked.  
**Classification**: RDF402 

[Download Schema](Schema_VMS_Action.zip) 

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| action | Action | Action taken by the VMS (Milking, Rejected, or Released unmilked) |
| action_code | Action Code | Action taken by the VMS (0=Milking; 1=Rejected; 4=Released unmilked) |
| animal_id | Animal ID | Farm-level unique animal ID |
| begin_time | Begin Time | Visit start time |
| date | Date | Visit start date |
| end_date | End Date | Visit end date |
| end_time | End Time | Visit end time |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | milk_vms_action | Action taken by the Voluntary Milking System (VMS) when cow enters the VMS, either to accept or reject the cow for milking, or to release cow unmilked. |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| action | false |  | Text | Action | Action taken by the VMS (Milking, Rejected, or Released unmilked) | Not a list | utf-8 |
| action_code | false |  | Numeric | Action Code | Action taken by the VMS (0=Milking; 1=Rejected; 4=Released unmilked) | Not a list | utf-8 |
| animal_id | false |  | Numeric | Animal ID | Farm-level unique animal ID | Not a list | utf-8 |
| begin_time | false |  | DateTime | Begin Time | Visit start time | Not a list | utf-8 |
| date | false |  | DateTime | Date | Visit start date | Not a list | utf-8 |
| end_date | false |  | DateTime | End Date | Visit end date | Not a list | utf-8 |
| end_time | false |  | DateTime | End Time | Visit end time | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: EidEIg3MR_4T2MRxb5tv0cU8CFMuX9Eo-4Px_zC5YKk0

| Layer | SAID |
| --- | --- |
| character_encoding | EpEJvl62S6ftfhgI9uCOQetFMrVhpDf6WGyLTHFE9iqY |
| information (en) | E5LE32nWR6RnBffW_Fnc7FadG5_FthVbUtjIqxRc9k00 |
| label (en) | ECWTZZKBEmZbsH3_m0MIchDsVlToHMLLOyq3XL8G-b5g |
| meta (en) | EgU5VP0Sk2Wv5ew-YrHifQf3RTfTsI1Knpu6h7rXY41k |
