---
layout: default  
title: Animal Events: Life Events 
parent: Ontario Dairy Research Centre  
---

## Schema information

**Name**: animal_events_life_events  
**Description**: Records of once-in-life events entered on DairyComp.  
**Classification**: RDF402 

[Download Schema](Schema_Animal_Events_Life_Events.zip) 

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| breeding_code | Breeding Code | Breeding code |
| date | Date | Date of event |
| dim | Days in Milk | If heifer (lact_n = 0), age in days at time of event. If cow (lact_n > 0), days in milk at time of event |
| event | Event | Event |
| lact_n | Lactation Number | Lactation number at time of event |
| protocol | Protocol | Protocol used |
| remark | Remark | Event remark |
| remark_code | Remark Code | Remark code |
| technician_code | Technician Code | Technician code |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | animal_events_life_events | Records of once-in-life events entered on DairyComp. |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | Animal ID | Farm-level unique animal ID | Not a list | utf-8 |
| breeding_code | false |  | Text | Breeding Code | Breeding code | Not a list | utf-8 |
| date | false |  | DateTime | Date | Date of event | Not a list | utf-8 |
| dim | false |  | Text | Days in Milk | If heifer (lact_n = 0), age in days at time of event. If cow (lact_n > 0), days in milk at time of event | Not a list | utf-8 |
| event | false |  | Text | Event | Event | Not a list | utf-8 |
| lact_n | false |  | Numeric | Lactation Number | Lactation number at time of event | Not a list | utf-8 |
| protocol | false |  | Text | Protocol | Protocol used | Not a list | utf-8 |
| remark | false |  | Text | Remark | Event remark | Not a list | utf-8 |
| remark_code | false |  | Text | Remark Code | Remark code | Not a list | utf-8 |
| technician_code | false |  | Text | Technician Code | Technician code | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: Ejb-VnURzuRyqArT0mZ_JH0he3nUnVz9Lp88378ump-o

| Layer | SAID |
| --- | --- |
| character_encoding | EEt9hP3aNU5wqANMuis45GvzTBgupHrwH6z_0jvRHB5c |
| information (en) | EH7wy7H2_sPlc4sY-lf6B9wcS4x0FBJemdR3uPcOke0E |
| label (en) | EDZVzp7SQ70Jlqbek0kagfSC7UKt1lcANX4YakN_KQfE |
| meta (en) | EH_PlpENrzs-weWKWi6Ons_P7jXcNlwy1TuZcWxBkqZs |
