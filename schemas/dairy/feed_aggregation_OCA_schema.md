---
layout: default  
title: Feed Aggregation
parent: Ontario Dairy Research Centre  
---

## Schema information

**Name**: feed_aggregation  
**Description**: Aggregated daily feed intakes for animals fed at the maternity & tie stalls and from Insentec bins. Daily intakes for Insentec data is the sum of all positive intakes per animal per day using data from the Insentec (FR) table. Please refer to the description of such table to learn how Insentec data was pre-treated.  
**Classification**: RDF402 

[Download Schema](Schema_Feed_Aggregation.zip) 

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level animal ID |
| date | Date | Date animal ate (Insentec) or was offered feed (maternity and tie stalls) |
| feed_carts_intake | Feed Cart Intake | Total intake from animal fed with the feed carts (Super Data Ranger and Orts carts). If null, animal was not at maternity/tie stalls or did not eat while there |
| insentec_intake | Insentec Intake | Sum of all positive intakes per animal per day using data from the Insentec (FR) table. If null, animal was not at a pen with an Insentec bin, or did not eat from an Insentec bin while there |
| total_intake | Total Intake | Sum of insentec_intake and feed_carts_intake |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | feed_aggregation | Aggregated daily feed intakes for animals fed at the maternity & tie stalls and from Insentec bins. Daily intakes for Insentec data is the sum of all positive intakes per animal per day using data from the Insentec (FR) table. Please refer to the description of such table to learn how Insentec data was pre-treated. |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | Animal ID | Farm-level animal ID | Not a list | utf-8 |
| date | false |  | DateTime | Date | Date animal ate (Insentec) or was offered feed (maternity and tie stalls) | Not a list | utf-8 |
| feed_carts_intake | false |  | Numeric | Feed Cart Intake | Total intake from animal fed with the feed carts (Super Data Ranger and Orts carts). If null, animal was not at maternity/tie stalls or did not eat while there | Not a list | utf-8 |
| insentec_intake | false |  | Numeric | Insentec Intake | Sum of all positive intakes per animal per day using data from the Insentec (FR) table. If null, animal was not at a pen with an Insentec bin, or did not eat from an Insentec bin while there | Not a list | utf-8 |
| total_intake | false |  | Numeric | Total Intake | Sum of insentec_intake and feed_carts_intake | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: EjWfUPCYvCyum7G7LdxYKRcbM0e6Tr--ds9BLLODyUAA

| Layer | SAID |
| --- | --- |
| character_encoding | E4s451cmAst2Q3AbLmvShGz36cC4g9VSAZUJmLEH1Xng |
| information (en) | EFiDsgKmUnUM6Ij2yZq9exRUjhCwHU7C-2glQsFYLtJw |
| label (en) | EC9HEBGl-Jt4Osr4K_xGY8e4zycDCjn3BuJx9xU1PvZA |
| meta (en) | EYNYyWOwO8yenZcj89GGiBSG2AEl9Tw32f9nDvzgvW1I |
