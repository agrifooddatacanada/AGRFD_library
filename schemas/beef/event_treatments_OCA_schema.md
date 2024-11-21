---
layout: default  
title: Event Treatments  
parent: Ontario Beef Research Centre
---

## Schema information

**Name**: Event Treatments  
**Description**: Disease diagnosis and treatments 

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

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| body_weight | false | Kilogram | Numeric | Body Weight | Body weight at time of treatment. Not all treatments have a body weight measured, but Herdtrax requires a body weight for every entry, therefore 1000 and 2000 are entered when body weights were not measured. | Not a list | utf-8 |
| date | false |  | DateTime | Date | Treatment or diagnosis date | Not a list | utf-8 |
| diagnosis | false |  | Text | Diagnosis | Diagnosis | Not a list | utf-8 |
| diagnosis_occurence | false |  | Text | Diagnosis Occurence | Occurence number of the same diagnosis for a given animal. Incremented by one for each consecutive occurence. | Not a list | utf-8 |
| event_id | false |  | Numeric | Event ID | Herdtrax's internal event ID | Not a list | utf-8 |
| herdtrax_id | false |  | Numeric | Herdtrax ID | Herdtrax's internal Animal ID | Not a list | utf-8 |
| oid | false |  | Numeric | Record ID | Internal database record ID | Not a list | utf-8 |
| protocol | false |  | Text | Protocol | Treament/drug protocol | Not a list | utf-8 |
| quantity | false |  | Numeric | Quantity | Treament/drug quantity | Not a list | utf-8 |
| route | false |  | Text | Route | Treament/drug route | Not a list | utf-8 |
| temperature | false | Celcius | Numeric | Temperature | Temperature at time of treatment | Not a list | utf-8 |
| treatment | false |  | Text | Treatment | Treament/drug administered | Not a list | utf-8 |
| unit | false |  | Text | Unit | Treament/drug unit | Not a list | utf-8 |
| withdrawal_date | false |  | DateTime | Withdrawal Date | Meat withdrawal date | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: EspW9l41AzMsYRZEI9lMwvku52SS0X81HrnGHPUmbkLQ

| Layer | SAID |
| --- | --- |
| character_encoding | EcaYG7tOokl2r2dNAW7TNxRr3bvacSHDkcT7VaZrcRGw |
| information (en) | Ejr0UiAWsJyma-sc4HwE5wcMP8vwfpOPJj5FLdvtePnM |
| label (en) | E7gn7OrGn7tCJdCqOtOU2yPPfYb36WInKOtlKc2kNV9Q |
| meta (en) | Ehhy0zY7kSS4RiZU-h8DoMq73n5ETDB9ohTQQo2qNM-c |
| unit | EMbPz1wgPazMexfmCHN9eGGQ0NPoVCXSeXwJ-BDTtp18 |

**Date created**: 2024-11-21 10:21:55

