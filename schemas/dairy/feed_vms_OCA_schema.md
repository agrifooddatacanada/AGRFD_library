---
layout: default  
title: Feed - Voluntary Milking System (VMS)
parent: Ontario Dairy Research Centre  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: feed_vms  
**Description**: Feed pellets dispensed to cows at the Voluntary Milking System (VMS) during milking. There is no scale to weigh the actual amount of feed consumed. Each record is the total amount (kg) of feed pellets dispensed hourly - e.g., hour = 14:00:00 and feed_dispensed = 1.5, therefore this cow ate 1.5 kg of feed from 1 pm to 2 pm. If a cow started milking at 03:55:00 and finished at 04:05:00, there will be two records for that session, one for the amount dispensed until 4 am, and another for the amount dispensed until 5 am. Milking start and end times are not necessarily the same times for feeding, i.e., a cow could start milking at 03:55:00, but only start eating at 04:01:00, therefore she would only have one record for that session to reflect the amount she ate until 5 am.  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  

[Download Schema](Schema_Feed_VMS.zip)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id |  | Farm-level unique animal ID |
| begin_date |  | Milking start date |
| begin_time |  | Milking start time |
| date |  | Date cow started milking |
| end_date |  | Milking end date |
| end_time |  | Milking end time |
| feed_dispensed |  | Amount (Kg) of feed pellets dispensed to animal, not necessarily the amount the animal ate |
| hour |  | Cut-off time to calculate amount of feed dispensed |
| session_n |  | Milking session number |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | feed_vms | Feed pellets dispensed to cows at the Voluntary Milking System (VMS) during milking. There is no scale to weigh the actual amount of feed consumed. Each record is the total amount (kg) of feed pellets dispensed hourly - e.g., hour = 14:00:00 and feed_dispensed = 1.5, therefore this cow ate 1.5 kg of feed from 1 pm to 2 pm. If a cow started milking at 03:55:00 and finished at 04:05:00, there will be two records for that session, one for the amount dispensed until 4 am, and another for the amount dispensed until 5 am. Milking start and end times are not necessarily the same times for feeding, i.e., a cow could start milking at 03:55:00, but only start eating at 04:01:00, therefore she would only have one record for that session to reflect the amount she ate until 5 am. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| begin_date | false |  | DateTime | utf-8 |
| begin_time | false |  | DateTime | utf-8 |
| date | false |  | DateTime | utf-8 |
| end_date | false |  | DateTime | utf-8 |
| end_time | false |  | DateTime | utf-8 |
| feed_dispensed | false |  | Numeric | utf-8 |
| hour | false |  | DateTime | utf-8 |
| session_n | false |  | Numeric | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id |  | Farm-level unique animal ID | Not a list |
| begin_date |  | Milking start date | Not a list |
| begin_time |  | Milking start time | Not a list |
| date |  | Date cow started milking | Not a list |
| end_date |  | Milking end date | Not a list |
| end_time |  | Milking end time | Not a list |
| feed_dispensed |  | Amount (Kg) of feed pellets dispensed to animal, not necessarily the amount the animal ate | Not a list |
| hour |  | Cut-off time to calculate amount of feed dispensed | Not a list |
| session_n |  | Milking session number | Not a list |

## Schema SAIDs

**Capture base**: E8eb0hZFMyeCSNe7cQ5JbM1jxc6gB7IwOLUGZFc2An4M

| Layer | SAID |
| --- | --- |
| character_encoding | EWvqDwNrcwSDcpOV1l21X1QUMdzJglDQxlF_hDqfzui4 |
| information (en) | EiowLSTDZXLdDCVjWZ9kq7hGUz0enTxTzwYZCswcsu7w |
| label (en) | EGG4t8cozetrXC71GD2BT4KhWD7NQwPFzCohXSYkAGG8 |
| meta (en) | ExnNBevBpiF7V_irT3TJZoMKORDvrmInWe7O0E8ckEeQ |

**Date created**: 2024-12-03 15:14:07

