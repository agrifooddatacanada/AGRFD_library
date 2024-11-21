---
layout: default  
title: Carcass Grade and Rib Dissection  
parent: Ontario Beef Research Centre
---

## Schema information

**Name**: Carcass Grade and Rib Dissection 
**Description**: Carcass grading and rib dissection data performed at UoG Animal Bioscience's Meat Lab  
**Classification**: RDF402  

[Download Schema](Schema_Meat_Carcass_Grade.zip)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Alpha-numeric ID of carcass | ID as written on animal's tag |
| body_fat | Body fat | Amount of adipose tissue in the live animal |
| bone_weight | Bone weight |  |
| date | Date of sampling |  |
| decl_bull | ID of declared bull | Animals declared bull |
| decl_cow | ID of declared cow | Animals declared cow |
| decl_heifer | ID of declared heifer | Animals declared heifer |
| decl_steer | ID of declared steer | Animals declared steer |
| discrepancies | Recorded discrepancies | Animals with discrepancies between input sheet and tracing data |
| fat_class_ac | Level of fat on carcass | Measured using Acceptable Carcass Grading. |
| fat_class_bga | Level of fat on carcass | Measured using Beed Grading and Application. |
| fat_class_ug | Level of fat on carcass | Measured using Ultrasound Grading. |
| fat_color | Fat color | Level of colouring on fat |
| grade_fat | Amount of subcutaneous fat on ribeye muscle | Numerical score reflects the amount of subcutaneous fat covering the ribeye muscle at the 12th rib. Measured using a grading ruler. |
| hot_carcass_weight | Hot carcas weight | Hot/unchilled weight post slaughter & removal of head hide intestinal weight and organs. Used to determine yield grade and dressing percentage |
| image_id | Image ID | ID corresponding to image in tracings folder |
| inter_fat | Inner fat | Amount of inter muscular fat |
| lean_color | lean_color | Level of colouring on lean meat |
| lean_weight | Weight of carcass | Weight of meat available for consumption or further processing after removal of fat and non-muscle tissues. |
| lean_yield_ac | Amount of lean meat tissue | Weight of lean meat from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Measured using Acceptable Carcass Grading. |
| lean_yield_bga | Amount of lean meat tissue | Weight of lean meat from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Measured using Beed Grading and Application. |
| lean_yield_ug | Amount of lean meat tissue | Weight of lean meat from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Measured using Ultrasound Grading. |
| live_weight | Live weight | Weight of animal prior to being slaughtered. |
| liver_weight | Liver weight |  |
| marbling | Level of marbling | Amount of intramuscular fat in lean tissue |
| muscle_class_ac | Degree od muscling. | Measured using Acceptable Carcass Grading. |
| muscle_class_bga | Degree od muscling. | Measured using Beed Grading and Application. |
| muscle_class_ug | Degree od muscling. | Measured using Ultrasound Grading. |
| oid | Record ID | Record ID |
| quality_grade_ac | Level of meat quality. | Measured using Acceptable Carcass Grading. |
| quality_grade_bga | Level of meat quality. | Measured using Beed Grading and Application. |
| quality_grade_ug | Level of meat quality. | Measured using Ultrasound Grading. |
| rib_eye_area_sqin | Area of ribeye in square inches. | Measured using a grid system |
| rib_eye_area_sqmm | Area of ribeye in square millimetres | Measured using a grid system |
| rib_eye_length_ac | Length of ribeye. | Measured along the length of the ribeye muscle from anterior to posterior. Measured using Acceptable Carcass Grading. |
| rib_eye_length_bga | Length of ribeye. | Measured along the length of the ribeye muscle from anterior to posterior. Measured using Beed Grading and Application. |
| rib_eye_length_ug | Length of ribeye. | Measured along the length of the ribeye muscle from anterior to posterior. Measured using Ultrasound Grading. |
| rib_eye_width_ac | Width of ribeye. | Measured at the widest point of the ribeye muscle. Measured using Acceptable Carcass Grading. |
| rib_eye_width_bga | Width of ribeye. | Measured at the widest point of the ribeye muscle. Measured using Beed Grading and Application. |
| rib_eye_width_ug | Width of ribeye. | Measured at the widest point of the ribeye muscle. Measured using Ultrasound Grading. |
| rib_fat1 | Amount of subcutaneous fat measurement 1 | Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib. Assessed using a grading ruler |
| rib_fat2 | Amount of subcutaneous fat measurement 2 | Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib. Assessed using a grading ruler |
| rib_fat3 | Amount of subcutaneous fat measurement 3 | Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib. Assessed using a grading ruler |
| rib_wt | Weight of rib section | Includes ribs and associated meat and fat |
| sub_fat | Amount of subcutaneous fat |  |
| yield_grade_ac | Percentage of carcass that is saleable at retail. | Y1 having the highest estimated yield and Y5 having the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat. Measured using Acceptable Carcass Grading. |
| yield_grade_bga | Percentage of carcass that is saleable at retail. | Y1 having the highest estimated yield and Y5 having the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat. Measured using Beed Grading and Application. |
| yield_grade_ug | Percentage of carcass that is saleable at retail. | Y1 having the highest estimated yield and Y5 having the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat. Measured using Ultrasound Grading. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | meat_carcass_grade | Carcass grading and rib dissection data performed at UoG Animal Bioscience's Meat Lab |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding |
| --- | --- | --- | --- | --- | --- | --- | --- |
| animal_id | false |  | Text | Alpha-numeric ID of carcass | ID as written on animal's tag | Not a list | utf-8 |
| body_fat | false | kg | Numeric | Body fat | Amount of adipose tissue in the live animal | Not a list | utf-8 |
| bone_weight | false | kg | Numeric | Bone weight |  | Not a list | utf-8 |
| date | false |  | Numeric | Date of sampling |  | Not a list | utf-8 |
| decl_bull | false |  | Text | ID of declared bull | Animals declared bull | Not a list | utf-8 |
| decl_cow | false |  | Text | ID of declared cow | Animals declared cow | Not a list | utf-8 |
| decl_heifer | false |  | Text | ID of declared heifer | Animals declared heifer | Not a list | utf-8 |
| decl_steer | false |  | Text | ID of declared steer | Animals declared steer | Not a list | utf-8 |
| discrepancies | false |  | Text | Recorded discrepancies | Animals with discrepancies between input sheet and tracing data | Not a list | utf-8 |
| fat_class_ac | false |  | Numeric | Level of fat on carcass | Measured using Acceptable Carcass Grading. | Not a list | utf-8 |
| fat_class_bga | false |  | Numeric | Level of fat on carcass | Measured using Beed Grading and Application. | Not a list | utf-8 |
| fat_class_ug | false |  | Numeric | Level of fat on carcass | Measured using Ultrasound Grading. | Not a list | utf-8 |
| fat_color | false |  | Text | Fat color | Level of colouring on fat | Not a list | utf-8 |
| grade_fat | false | mm | Numeric | Amount of subcutaneous fat on ribeye muscle | Numerical score reflects the amount of subcutaneous fat covering the ribeye muscle at the 12th rib. Measured using a grading ruler. | Not a list | utf-8 |
| hot_carcass_weight | false | kg | Numeric | Hot carcas weight | Hot/unchilled weight post slaughter & removal of head hide intestinal weight and organs. Used to determine yield grade and dressing percentage | Not a list | utf-8 |
| image_id | false |  | Text | Image ID | ID corresponding to image in tracings folder | Not a list | utf-8 |
| inter_fat | false | kg | Numeric | Inner fat | Amount of inter muscular fat | Not a list | utf-8 |
| lean_color | false |  | Text | lean_color | Level of colouring on lean meat | Not a list | utf-8 |
| lean_weight | false | kg | Numeric | Weight of carcass | Weight of meat available for consumption or further processing after removal of fat and non-muscle tissues. | Not a list | utf-8 |
| lean_yield_ac | false | % | Numeric | Amount of lean meat tissue | Weight of lean meat from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Measured using Acceptable Carcass Grading. | Not a list | utf-8 |
| lean_yield_bga | false | % | Numeric | Amount of lean meat tissue | Weight of lean meat from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Measured using Beed Grading and Application. | Not a list | utf-8 |
| lean_yield_ug | false | % | Numeric | Amount of lean meat tissue | Weight of lean meat from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Measured using Ultrasound Grading. | Not a list | utf-8 |
| live_weight | false | kg | Numeric | Live weight | Weight of animal prior to being slaughtered. | Not a list | utf-8 |
| liver_weight | false | kg | Text | Liver weight |  | Not a list | utf-8 |
| marbling | false |  | Text | Level of marbling | Amount of intramuscular fat in lean tissue | Not a list | utf-8 |
| muscle_class_ac | false |  | Numeric | Degree od muscling. | Measured using Acceptable Carcass Grading. | Not a list | utf-8 |
| muscle_class_bga | false |  | Numeric | Degree od muscling. | Measured using Beed Grading and Application. | Not a list | utf-8 |
| muscle_class_ug | false |  | Numeric | Degree od muscling. | Measured using Ultrasound Grading. | Not a list | utf-8 |
| oid | false |  | Numeric | Record ID | Record ID | Not a list | utf-8 |
| quality_grade_ac | false |  | Numeric | Level of meat quality. | Measured using Acceptable Carcass Grading. | Not a list | utf-8 |
| quality_grade_bga | false |  | Text | Level of meat quality. | Measured using Beed Grading and Application. | Not a list | utf-8 |
| quality_grade_ug | false |  | Text | Level of meat quality. | Measured using Ultrasound Grading. | Not a list | utf-8 |
| rib_eye_area_sqin | false | sq in. | Numeric | Area of ribeye in square inches. | Measured using a grid system | Not a list | utf-8 |
| rib_eye_area_sqmm | false | sq mm. | Numeric | Area of ribeye in square millimetres | Measured using a grid system | Not a list | utf-8 |
| rib_eye_length_ac | false | in | Numeric | Length of ribeye. | Measured along the length of the ribeye muscle from anterior to posterior. Measured using Acceptable Carcass Grading. | Not a list | utf-8 |
| rib_eye_length_bga | false | in | Numeric | Length of ribeye. | Measured along the length of the ribeye muscle from anterior to posterior. Measured using Beed Grading and Application. | Not a list | utf-8 |
| rib_eye_length_ug | false | in | Numeric | Length of ribeye. | Measured along the length of the ribeye muscle from anterior to posterior. Measured using Ultrasound Grading. | Not a list | utf-8 |
| rib_eye_width_ac | false | in | Numeric | Width of ribeye. | Measured at the widest point of the ribeye muscle. Measured using Acceptable Carcass Grading. | Not a list | utf-8 |
| rib_eye_width_bga | false | in | Numeric | Width of ribeye. | Measured at the widest point of the ribeye muscle. Measured using Beed Grading and Application. | Not a list | utf-8 |
| rib_eye_width_ug | false | in | Numeric | Width of ribeye. | Measured at the widest point of the ribeye muscle. Measured using Ultrasound Grading. | Not a list | utf-8 |
| rib_fat1 | false | mm | Numeric | Amount of subcutaneous fat measurement 1 | Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib. Assessed using a grading ruler | Not a list | utf-8 |
| rib_fat2 | false | mm | Numeric | Amount of subcutaneous fat measurement 2 | Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib. Assessed using a grading ruler | Not a list | utf-8 |
| rib_fat3 | false | mm | Numeric | Amount of subcutaneous fat measurement 3 | Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib. Assessed using a grading ruler | Not a list | utf-8 |
| rib_wt | false | kg | Numeric | Weight of rib section | Includes ribs and associated meat and fat | Not a list | utf-8 |
| sub_fat | false | kg | Numeric | Amount of subcutaneous fat |  | Not a list | utf-8 |
| yield_grade_ac | false |  | Numeric | Percentage of carcass that is saleable at retail. | Y1 having the highest estimated yield and Y5 having the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat. Measured using Acceptable Carcass Grading. | Not a list | utf-8 |
| yield_grade_bga | false |  | Text | Percentage of carcass that is saleable at retail. | Y1 having the highest estimated yield and Y5 having the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat. Measured using Beed Grading and Application. | Not a list | utf-8 |
| yield_grade_ug | false |  | Text | Percentage of carcass that is saleable at retail. | Y1 having the highest estimated yield and Y5 having the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat. Measured using Ultrasound Grading. | Not a list | utf-8 |

## Schema SAIDs

**Capture base**: ET0CLrR-VEXJu7eOCZAcbA7S-7MdkKFhP7RwVKng3LTc

| Layer | SAID |
| --- | --- |
| character_encoding | E6iY3f6vatZFEpd-UCWVL0hEVOn0wBqbdko9dFLD9z9c |
| information (en) | Et0iMXjAqeskhjakhPf7tL0E28XlrutfaSyASBq9X764 |
| label (en) | ETlDQtQkBeTor6untiJ1Ve9nVU8VhUJ3jfj8AxNntYsQ |
| meta (en) | Ed_HBszslS9gME4BjHIXuTjZVChNC3OWtWF_xgOCrZDA |
| unit | EIVJE7_BDioDwJ2hKrHcdWm6f_r4DiFNfm4pLKsRCrL0 |

**Date created**: 2024-11-21 10:22:51

