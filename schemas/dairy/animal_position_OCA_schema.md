---
layout: default  
title: Animal Position
parent: Ontario Dairy Research Centre   
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: animal_position  
**Description**: Daily animal position at the barn extracted from SCR collars, DairyComp's log files, and Insentec VR files. Animal position from SCR is the last position on the day, whereas DairyComp shows all move events on a day or is implied to be the same as the last one informed until animal dies or leaves the herd. Positions from Insentec system is based on bin visits.  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  

[Download Schema](Schema_Animal_Position.zip)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| date | Date | Date position (pen number) was recorded |
| dc_logs_event_info | Information About Event | Information about event. Sold: Animal sold. Died: Animal left the herd. Moved: Animal was moved to pen indicated on dc_logs_pen. Implied Position: dc_logs_pen was implied from previous 'Moved' event. |
| dc_logs_event_time | Event Time Logged in DairyComp | Time event was recorded on DairyComp log. Empty field means that pen number did not actually appear on the logs, thus there is no time available. |
| dc_logs_pen | DairyComp Pen Number on Log File | Pen number indicated on the log file of DairyComp when an animal change positions (Move event), or pen number implied from last informed position until animal is sold or leaves the herd. |
| insentec_first_pen_visit | First Insentec Pen Visit | First time animal visited an Insentec bin on that pen and day |
| insentec_last_pen_visit | Last Insentec Pen Visit | Last time animal visited an Insentec bin on that pen and day |
| insentec_pen | Insentec Pen Number | Pen number based on bins visited by animal on Insentec system. If pens were connected due to trial needs, an animal might have more than one insentec_pen per day. |
| scr_pen | SCR Pen | Pen number indicated by the SCR/Allflex tag at the end of the day |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | animal_position | Daily animal position at the barn extracted from SCR collars, DairyComp's log files, and Insentec VR files. Animal position from SCR is the last position on the day, whereas DairyComp shows all move events on a day or is implied to be the same as the last one informed until animal dies or leaves the herd. Positions from Insentec system is based on bin visits. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | utf-8 |
| date | false |  | DateTime | utf-8 |
| dc_logs_event_info | false |  | Text | utf-8 |
| dc_logs_event_time | false |  | DateTime | utf-8 |
| dc_logs_pen | false |  | Numeric | utf-8 |
| insentec_first_pen_visit | false |  | DateTime | utf-8 |
| insentec_last_pen_visit | false |  | DateTime | utf-8 |
| insentec_pen | false |  | Numeric | utf-8 |
| scr_pen | false |  | Numeric | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID | Not a list |
| date | Date | Date position (pen number) was recorded | Not a list |
| dc_logs_event_info | Information About Event | Information about event. Sold: Animal sold. Died: Animal left the herd. Moved: Animal was moved to pen indicated on dc_logs_pen. Implied Position: dc_logs_pen was implied from previous 'Moved' event. | Not a list |
| dc_logs_event_time | Event Time Logged in DairyComp | Time event was recorded on DairyComp log. Empty field means that pen number did not actually appear on the logs, thus there is no time available. | Not a list |
| dc_logs_pen | DairyComp Pen Number on Log File | Pen number indicated on the log file of DairyComp when an animal change positions (Move event), or pen number implied from last informed position until animal is sold or leaves the herd. | Not a list |
| insentec_first_pen_visit | First Insentec Pen Visit | First time animal visited an Insentec bin on that pen and day | Not a list |
| insentec_last_pen_visit | Last Insentec Pen Visit | Last time animal visited an Insentec bin on that pen and day | Not a list |
| insentec_pen | Insentec Pen Number | Pen number based on bins visited by animal on Insentec system. If pens were connected due to trial needs, an animal might have more than one insentec_pen per day. | Not a list |
| scr_pen | SCR Pen | Pen number indicated by the SCR/Allflex tag at the end of the day | Not a list |

## Schema SAIDs

**Capture base**: E8oY6UBImmIxQelTwpfPtmTVqV6snzBsUYpDj1wXsM9Q

| Layer | SAID |
| --- | --- |
| character_encoding | EePCEEWV_TosnfeOgyuxr_7jAFoCDcJLs1SS51phlxn0 |
| information (en) | EqKE8uOHyJ_OYVaeG-PUx3Z5oaM2fQyvvILUKyumhIA4 |
| label (en) | E8SL6nQOqitmO_3lF1hPj6nIsqzDyMVKs6pfJZkcTYZ0 |
| meta (en) | Eu6G-muelLaXp3HDU3UqXgRwVaAu5GZQw4_GYMelAuSQ |

**Date created**: 2024-12-03 15:12:14

