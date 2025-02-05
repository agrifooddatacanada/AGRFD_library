---
layout: default  
title: Animal Events - Treatments  
parent: Ontario Beef Research Centre 
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: event_treatments  
**Description**: Disease diagnosis and treatments  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca

[Download Schema](Schema_Event_Treatments.zip)  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| body_weight | Body Weight | Body weight at time of treatment. Not all treatments have a body weight measured, but Herdtrax requires a body weight for every entry, therefore 1000 and 2000 are entered when body weights were not measured. |
| date | Date | Treatment or diagnosis date |
| diagnosis | Diagnosis | Diagnosis |
| diagnosis_occurence | Diagnosis Occurence | Occurence number of the same diagnosis for a given animal. Incremented by one for each consecutive occurence. |
| event_id | Event ID | Herdtrax's internal event ID |
| herdtrax_id | Herdtrax ID | Herdtrax's internal Animal ID |
| oid | Record ID | Internal database record ID |
| protocol | Protocol | Treament/drug protocol |
| quantity | Quantity | Treament/drug quantity |
| route | Route | Treament/drug route |
| temperature | Temperature | Temperature at time of treatment |
| treatment | Treatment | Treament/drug administered |
| unit | Unit | Treament/drug unit |
| withdrawal_date | Withdrawal Date | Meat withdrawal date |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | event_treatments | Disease diagnosis and treatments |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| body_weight | false | Kilogram | Numeric | utf-8 |
| date | false |  | DateTime | utf-8 |
| diagnosis | false |  | Text | utf-8 |
| diagnosis_occurence | false |  | Text | utf-8 |
| event_id | false |  | Numeric | utf-8 |
| herdtrax_id | false |  | Numeric | utf-8 |
| oid | false |  | Numeric | utf-8 |
| protocol | false |  | Text | utf-8 |
| quantity | false |  | Numeric | utf-8 |
| route | false |  | Text | utf-8 |
| temperature | false | Celcius | Numeric | utf-8 |
| treatment | false |  | Text | utf-8 |
| unit | false |  | Text | utf-8 |
| withdrawal_date | false |  | DateTime | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| body_weight | Body Weight | Body weight at time of treatment. Not all treatments have a body weight measured, but Herdtrax requires a body weight for every entry, therefore 1000 and 2000 are entered when body weights were not measured. | Not a list |
| date | Date | Treatment or diagnosis date | Not a list |
| diagnosis | Diagnosis | Diagnosis | Not a list |
| diagnosis_occurence | Diagnosis Occurence | Occurence number of the same diagnosis for a given animal. Incremented by one for each consecutive occurence. | Not a list |
| event_id | Event ID | Herdtrax's internal event ID | Not a list |
| herdtrax_id | Herdtrax ID | Herdtrax's internal Animal ID | Not a list |
| oid | Record ID | Internal database record ID | Not a list |
| protocol | Protocol | Treament/drug protocol | Not a list |
| quantity | Quantity | Treament/drug quantity | Not a list |
| route | Route | Treament/drug route | Not a list |
| temperature | Temperature | Temperature at time of treatment | Not a list |
| treatment | Treatment | Treament/drug administered | Not a list |
| unit | Unit | Treament/drug unit | Not a list |
| withdrawal_date | Withdrawal Date | Meat withdrawal date | Not a list |

## Schema SAIDs

**Capture base**: EspW9l41AzMsYRZEI9lMwvku52SS0X81HrnGHPUmbkLQ

| Layer | SAID |
| --- | --- |
| character_encoding | EcaYG7tOokl2r2dNAW7TNxRr3bvacSHDkcT7VaZrcRGw |
| information (en) | Ejr0UiAWsJyma-sc4HwE5wcMP8vwfpOPJj5FLdvtePnM |
| label (en) | E7gn7OrGn7tCJdCqOtOU2yPPfYb36WInKOtlKc2kNV9Q |
| meta (en) | Ehhy0zY7kSS4RiZU-h8DoMq73n5ETDB9ohTQQo2qNM-c |
| unit | EMbPz1wgPazMexfmCHN9eGGQ0NPoVCXSeXwJ-BDTtp18 |

**Date created**: 2024-12-03 15:20:10

