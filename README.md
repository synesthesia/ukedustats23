# UK Government education statistics 2023

This repository contains the UK government Education statistics for reporting year 2023 downlaoded and unpacked for easy online access for analysis.

## Source

[Education and training statistics for the UK 2023](https://explore-education-statistics.service.gov.uk/find-statistics/education-and-training-statistics-for-the-uk/2023)

## Files

All in CSV format

|File viewer|Raw CSV|
|----|----|
|[Schools](./data/uk_schools.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_schools.csv)|
|[Pupils](./data/uk_pupils.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_pupils.csv)|
|[Teachers](./data/uk_teachers.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_teachers.csv)|
|[Pupil/Teacher Ratios](./data/uk_pupil_teacher_ratios.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_pupil_teacher_ratios.csv)|
|[Further Education Students](./data/uk_post_compulsory_education_fe_students.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_post_compulsory_education_fe_students.csv)|
|[Higher Education Students](./data/uk_post_compulsory_education_he_students.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_post_compulsory_education_he_students.csv)|
|[FE and HE Providers](./data/uk_post_compulsory_education_institutions.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_post_compulsory_education_institutions.csv)|
|[UK NEET data (Not in Education, Employment or Training)](./data/uk_neet.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_neet.csv)|
|[Highest qualification among 19-64 year olds](./data//uk_highest_qualifications.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_highest_qualifications.csv)|
|[Education expenditure UK](./data/uk_expenditure.csv)|[CSV](https://raw.githubusercontent.com/synesthesia/ukedustats23/master/data/uk_expenditure.csv)

## Data guidance

### Description

This document describes the contents of the underlying data files accompanying the ‘education and training’ statistics publication. There is a Methodology document that is linked under ‘Useful information’ at the top of the release, that contains further information on the statistics published here.

### Coverage

This release compiles information on education systems across the United Kingdom.

### File formats and conventions

Symbols used in the underlying data are as follows:

- ‘z’ when an observation is not applicable
- ‘x’ when data is unavailable for other reasons
- ‘c’ confidential data
- ‘low’ rounds to 0, but is not 0

### Data files

#### Schools

Filename: uk_schools.csv
Geographic levels: National; Regional
Time period: 2015/16 to 2022/23
Content summary: This file contains information on the number of schools in the UK, by school type.

Variable names and descriptions for this file are provided below:

Variable name  |  Variable description
---------  |  -----------------
phase      |  School type
t_schools  |  Number of schools

Footnotes:

1. Primary and secondary figures include middle schools as deemed. Secondary schools include all-through schools.
2. In England, special schools include alternative provision (https://explore-education-statistics.service.gov.uk/glossary#alternative-provision) schools.
3. In Scotland, nursery figures include all providers of funded Early Learning and Childcare, except childminders.
4. Figures for independent schools in Scotland are unavailable.
5. Figures for independent schools in Wales are unavailable for 2019/20.
6. Independent schools includes non-maintained special schools.


#### Pupils

Filename: uk_pupils.csv
Geographic levels: National; Regional
Time period: 2015/16 to 2022/23
Content summary: This file contains information on the number of pupils in the UK, by age, sex and school type.

Variable names and descriptions for this file are provided below:

Variable name  |  Variable description
--------  |  ----------------
age       |  Age
gender    |  Gender
phase     |  School type
t_pupils  |  Number of pupils

Footnotes:

1. Primary and secondary figures include middle schools as deemed. Secondary schools include all-through schools.
2. In England, special schools include alternative provision (https://explore-education-statistics.service.gov.uk/glossary#alternative-provision) schools.
3. In Scotland, nursery figures include all providers of funded Early Learning and Childcare, except childminders.
4. Figures for independent schools in Scotland are unavailable.
5. Figures for independent schools in Wales are unavailable for 2019/20.
6. Independent schools includes non-maintained special schools.
7. In Scotland, Early Learning and Childcare pupil numbers by sex are unavailable.
8. In Northern Ireland, independent school pupil numbers by sex are unavailable.


#### Teachers

Filename: uk_teachers.csv
Geographic levels: National; Regional
Time period: 2015/16 to 2022/23
Content summary: This file contains information on the number of teachers in the UK, by sex and school type.

Variable names and descriptions for this file are provided below:

Variable name   |  Variable description
--------------  |  ---------------------------------------
gender          |  Gender
phase           |  School type
t_fte_teachers  |  Full-time equivalent number of teachers

Footnotes:

1. Primary and secondary figures include middle schools as deemed. Secondary schools include all-through schools.
2. In England, special schools include alternative provision (https://explore-education-statistics.service.gov.uk/glossary#alternative-provision) schools.
3. In Scotland, nursery figures include all providers of funded Early Learning and Childcare, except childminders.
4. Figures for independent schools in Scotland are unavailable.
5. Figures for independent schools in Wales are unavailable for 2019/20.
6. Totals includes those whose gender identity is other or unclassified.


####  Pupil teacher ratios (PTRs)

Filename: uk_pupil_teacher_ratios.csv
Geographic levels: National; Regional
Time period: 2015/16 to 2022/23
Content summary: This file contains information on pupil to teacher ratios (PTRs) in schools in the UK, by school type.

Variable names and descriptions for this file are provided below:

Variable name        |  Variable description
-------------------  |  -------------------
phase                |  School type
pupil_teacher_ratio  |  Pupil-teacher ratio

Footnotes:

1. In England, special schools include alternative provision (https://explore-education-statistics.service.gov.uk/glossary#alternative-provision) schools.
2. In England, the primary pupil-teacher ratio includes local authority (LA) maintained nurseries.


#### Further education students

Filename: uk_post_compulsory_education_fe_students.csv
Geographic levels: National
Time period: 2015/16 to 2021/22
Content summary: This file contains information on the number of further education students in the UK, by sex, age and mode of study.

Variable names and descriptions for this file are provided below:

Variable name  |  Variable description
-------------  |  ---------------------
age            |  Age
gender         |  Gender
mode_of_study  |  Mode of study
t_students     |  Number of FE students

Footnotes:

1. Totals include further education students at further education colleges or higher education providers.
2. In England, student numbers by mode of study (e.g. full-time, part-time, work-based learning) are unavailable.
3. Totals includes those whose gender identity is other or unclassified.
4. Figures are rounded to the nearest 5 and 'low' indicates a base value of fewer than 2.5. Where data shows 'x' this indicates data is unavailable, 'z' indicates data is not applicable, and 'c' indicates data is suppressed.


####  Higher education students

Filename: uk_post_compulsory_education_he_students.csv
Geographic levels: National
Time period: 2016/17 to 2021/22
Content summary: This file contains information on the number of higher education students in the UK, broken down by sex, level of education, mode of study, subject group and domicile.

Variable names and descriptions for this file are provided below:

Variable name  |  Variable description
-------------  |  ---------------------
domicile       |  Domicile
gender         |  Gender
level          |  Level of education
mode_of_study  |  Mode of study
subject        |  Subject group
t_students     |  Number of HE students

Footnotes:

1. Subject totals do not include Higher Education students on courses in further education colleges in Northern Ireland.
2. 2020/21 student numbers are not comparable to previous years due to a methodology change.
3. Totals includes those whose gender identity is other or unclassified.
4. Figures are rounded to the nearest 5 and 'low' indicates a base value of fewer than 2.5. Where data shows 'x' this indicates data is unavailable, 'z' indicates data is not applicable, and 'c' indicates data is suppressed.


#### Further and higher education providers

Filename: uk_post_compulsory_education_institutions.csv
Geographic levels: National
Time period: 2015/16 to 2021/22
Content summary: This file contains information on the number of further and higher education providers in the UK.

Variable names and descriptions for this file are provided below:

Variable name   |  Variable description
--------------  |  ----------------------
provider_type   |  Provider type
t_institutions  |  Number of institutions


#### UK NEET data

Filename: uk_neet.csv
Geographic levels: National
Time period: 2001 to 2023
Content summary: This file contains information in the number and percentage of young adults (aged 16-24) who are not in education, employment or training (NEET) in the UK, by sex.

Variable names and descriptions for this file are provided below:

Variable name        |  Variable description
-------------------  |  ---------------------------------------
age                  |  Age
gender               |  Gender
number               |  Number of people
percent              |  Percentage of relevant population group
population_category  |  Population category
quarter              |  Quarter


####  Highest qualification among 19-64 year olds

Filename: uk_highest_qualifications.csv
Geographic levels: National
Time period: 2022
Content summary: This file contains information on the highest qualification of adults (aged 19-64) in the UK, by sex.

Variable names and descriptions for this file are provided below:

Variable name        |  Variable description
-------------------  |  ---------------------------------------
age                  |  Age
gender               |  Gender
number               |  Number of people in thousands
percent              |  Percentage of relevant population group
population_category  |  Population category

Footnotes:

1. Scottish Credit and Qualifications Framework (SCQF) levels used in Scotland are not directly comparable to NQF levels used in England/Wales/Northern Ireland. Figures relating to levels 5, 6 and 7 have been provided as the closest match to NQF levels 2, 3 and 4 respectively. Figures for the UK have been calculated using the NQF levels assigned to Scottish qualifications in the Labour Force Survey.
2. 'z' indicates data is not applicable.


#### Education expenditure UK

Filename: uk_expenditure.csv
Geographic levels: National
Time period: 2015-16 to 2022-23
Content summary: This file contains information on government expenditure in education in the UK.

Variable names and descriptions for this file are provided below:

Variable name                      |  Variable description
---------------------------------  |  ------------------------------------------
education_function                 |  Education function
expenditure_level                  |  Expenditure level
expenditure_type                   |  Expenditure type
pt_expenditure_of_gdp              |  Total expenditure as a percentage of GDP
t_expenditure_millions             |  Total expenditure (millions)
t_expenditure_real_terms_millions  |  Total expenditure in real terms (millions)

Footnotes:

1. In England, secondary education includes expenditure on central government academies which will also cover some schools in primary education.
2. Totals exclude expenditure for education not definable by level.

