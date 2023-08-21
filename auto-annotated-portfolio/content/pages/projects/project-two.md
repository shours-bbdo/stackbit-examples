---
type: ProjectLayout
title: Healthcare project
colors: colors-a
date: '2021-12-20'
client: SCCM
description: >-
  This project was done in collaboration with clinicians to address real-world
  problems in healthcare using existing databases. Our problem statement was to
  check if patients were given different sedative drugs based on ethnicity, race
  or other factors.
featuredImage:
  type: ImageBlock
  url: /images/sccm-logo.png
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: /images/sccm-logo.png
  altText: Project image
---
This project was part of a [datathon](https://sccm.org/Research/Discovery-Research-Network/datascience/Datathon) with Society of Critical Care Medicine (SCCM), which involved coloration with clinicians and pharmacists to develop a data-driven model for care of critically ill patients using large health record databases.

#### Problem Description:

> Are there differences in sedative agent selection in adult patients on invasive mechanical ventilation based on race or ethnicity.

#### Databases:

We used two critical care databases:[ MIMIC-IV](https://physionet.org/content/mimiciv/2.2/) (Medical Information Mart for Intensive Care) database and the [eICU collborative research database. ](https://eicu-crd.mit.edu/about/eicu/)

#### BigQuery and Colab:

We used [BigQuery](https://console.cloud.google.com/bigquery?project=sccm-datathon) to easily explore the large datasets using SQL.

See example code on my [github](https://github.com/sshourie/SCCM-hackathon/tree/main) repository.

**Tags:** Python, BigQuery, SQL
