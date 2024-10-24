---
layout: default  
title: Milk Voluntary Milking System(VMS) milking data  
parent: Ontario Dairy Research Centre
---

## Schema information

**Name**: milk_vms  
**Description**: Data from the Voluntary Milking System (VMS)  
**Classification**: RDF402

[Download Schema](Schema_Milk_VMS.zip)  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| avg_occ | Average OCC | Average online cell counter |
| begin_time | Begin time | Milking start time |
| conductivity_lf | Conductivity left front | Conductivity on left front teat |
| conductivity_lr | Conductivity left rear | Conductivity on left rear teat |
| conductivity_rf | Conductivity right front | Conductivity on right front teat |
| conductivity_rr | Conductivity right rear | Conductivity on right rear teat |
| date | Date | Milking start date |
| dim | Days in milk | Days in milk |
| duration | Duration | Milking duration |
| end_date | End date | Milking end date |
| end_time | End time | Milking end time |
| expected_yield | Expected yield | Total Expected Yield |
| incomplete | Incomplete | Number of incomplete milkings |
| kickoff | Kickoff | Number of kickoffs |
| lact_n | Lactation number | Lactation number |
| mean_flow_lf | Mean flow left front | Mean milking flow on left front teat |
| mean_flow_lr | Mean flow left rear | Mean milking flow on left rear teat |
| mean_flow_rf | Mean flow right front | Mean milking flow on right front teat |
| mean_flow_rr | Mean flow right rear | Mean milking flow on right rear teat |
| not_milked_teats | Not milked teats | Number of teats not milked |
| peak_flow_lf | Peak flow left front | Peak milking flow on left front teat |
| peak_flow_lr | Peak flow left rear | Peak milking flow on left rear teat |
| peak_flow_rf | Peak flow right front | Peak milking flow on right front teat |
| peak_flow_rr | Peak flow right rear | Peak milking flow on right rear teat |
| quarter_lf_yield | Left front quarter yield | Milk yield on left front teat |
| quarter_lr_yield | Left rear quarter yield | Milk yield on left rear teat |
| quarter_rf_yield | Right front quarter yield | Milk yield on right front teat |
| quarter_rr_yield | Right rear quarter yield | Milk yield on right rear teat |
| sample_tube | Sample tube | Sample tube number (0-140) |
| sample_tube_position | Sample tube position | Sample tube position (0-70) |
| sample_tube_rack | Sample tube rack | Sample tube rack number (0-2) |
| session_n | Session number | Milking session number |
| total_yield | Total yield | Total milk yield |
| yield_expected_lf | Expected yield left front | Expected milk yield on left front teat |
| yield_expected_lr | Expected yield left rear | Expected milk yield on left rear teat |
| yield_expected_rf | Expected yield right front | Expected milk yield on right front teat |
| yield_expected_rr | Expected yield right rear | Expected milk yield on right rear teat |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | milk_vms | Data from the Voluntary Milking System (VMS) |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| animal_id | false |  | Numeric | Animal ID | Farm-level unique animal ID | Not a list | utf-8 |
| avg_occ | false | *1000 cells/m | Numeric | Average OCC | Average online cell counter | Not a list | utf-8 |
| begin_time | false |  | DateTime | Begin time | Milking start time | Not a list | utf-8 |
| conductivity_lf | false | mS/cm | Numeric | Conductivity left front | Conductivity on left front teat | Not a list | utf-8 |
| conductivity_lr | false | mS/cm | Numeric | Conductivity left rear | Conductivity on left rear teat | Not a list | utf-8 |
| conductivity_rf | false | mS/cm | Numeric | Conductivity right front | Conductivity on right front teat | Not a list | utf-8 |
| conductivity_rr | false | mS/cm | Numeric | Conductivity right rear | Conductivity on right rear teat | Not a list | utf-8 |
| date | false |  | DateTime | Date | Milking start date | Not a list | utf-8 |
| dim | false |  | Numeric | Days in milk | Days in milk | Not a list | utf-8 |
| duration | false |  | DateTime | Duration | Milking duration | Not a list | utf-8 |
| end_date | false |  | DateTime | End date | Milking end date | Not a list | utf-8 |
| end_time | false |  | DateTime | End time | Milking end time | Not a list | utf-8 |
| expected_yield | false | Kg | Numeric | Expected yield | Total Expected Yield | Not a list | utf-8 |
| incomplete | false |  | Numeric | Incomplete | Number of incomplete milkings | Not a list | utf-8 |
| kickoff | false |  | Numeric | Kickoff | Number of kickoffs | Not a list | utf-8 |
| lact_n | false |  | Numeric | Lactation number | Lactation number | Not a list | utf-8 |
| mean_flow_lf | false | Kg/min | Numeric | Mean flow left front | Mean milking flow on left front teat | Not a list | utf-8 |
| mean_flow_lr | false | Kg/min | Numeric | Mean flow left rear | Mean milking flow on left rear teat | Not a list | utf-8 |
| mean_flow_rf | false | Kg/min | Numeric | Mean flow right front | Mean milking flow on right front teat | Not a list | utf-8 |
| mean_flow_rr | false | Kg/min | Numeric | Mean flow right rear | Mean milking flow on right rear teat | Not a list | utf-8 |
| not_milked_teats | false |  | Numeric | Not milked teats | Number of teats not milked | Not a list | utf-8 |
| peak_flow_lf | false | Kg/min | Numeric | Peak flow left front | Peak milking flow on left front teat | Not a list | utf-8 |
| peak_flow_lr | false | Kg/min | Numeric | Peak flow left rear | Peak milking flow on left rear teat | Not a list | utf-8 |
| peak_flow_rf | false | Kg/min | Numeric | Peak flow right front | Peak milking flow on right front teat | Not a list | utf-8 |
| peak_flow_rr | false | Kg/min | Numeric | Peak flow right rear | Peak milking flow on right rear teat | Not a list | utf-8 |
| quarter_lf_yield | false | Kg | Numeric | Left front quarter yield | Milk yield on left front teat | Not a list | utf-8 |
| quarter_lr_yield | false | Kg | Numeric | Left rear quarter yield | Milk yield on left rear teat | Not a list | utf-8 |
| quarter_rf_yield | false | Kg | Numeric | Right front quarter yield | Milk yield on right front teat | Not a list | utf-8 |
| quarter_rr_yield | false | Kg | Numeric | Right rear quarter yield | Milk yield on right rear teat | Not a list | utf-8 |
| sample_tube | false |  | Numeric | Sample tube | Sample tube number (0-140) | Not a list | utf-8 |
| sample_tube_position | false |  | Numeric | Sample tube position | Sample tube position (0-70) | Not a list | utf-8 |
| sample_tube_rack | false |  | Numeric | Sample tube rack | Sample tube rack number (0-2) | Not a list | utf-8 |
| session_n | false |  | Numeric | Session number | Milking session number | Not a list | utf-8 |
| total_yield | false | Kg | Numeric | Total yield | Total milk yield | Not a list | utf-8 |
| yield_expected_lf | false | Kg | Numeric | Expected yield left front | Expected milk yield on left front teat | Not a list | utf-8 |
| yield_expected_lr | false | Kg | Numeric | Expected yield left rear | Expected milk yield on left rear teat | Not a list | utf-8 |
| yield_expected_rf | false | Kg | Numeric | Expected yield right front | Expected milk yield on right front teat | Not a list | utf-8 |
| yield_expected_rr | false | Kg | Numeric | Expected yield right rear | Expected milk yield on right rear teat | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: E0mOCMnqiyaSieuY1dTf2oTgRztV_dNBb4nmG6vgB1s8

| Layer | SAID |
| --- | --- |
| character_encoding | EOALyN9W51nd_vev5AbjjHbBvqp42vzqNOo1GPqu2wEs |
| information (en) | Ek5VX9jPU81XYc4cdPEoE384iMUWLA9E5pd-wo-RZiv8 |
| label (en) | ETyviV4wVQS370q3IGmSNk5gnRpM7C274Og3pL_kawdE |
| meta (en) | EuJaw0rvRApBgLniVwc8hfxun7z3LJdjXil3O_JYuXxU |
| unit | EgXwbElxBAphdxVCIxrELTNTz-j6LJ_d4mH218bNQ0dk |
