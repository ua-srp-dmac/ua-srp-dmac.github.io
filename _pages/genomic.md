---
title: "Genomic Data"
permalink: /data-standard/genomic/
layout: single
author_profile: false
sidebar:
  nav: "data-standard"
---

## File Naming Convention

File names should include the following fields, separated by "-" and followed by the file extension (.fastq, .bam).

+ **Lab:** the first 3 letters of the PI's last name, in all caps
+ **Date:** formatted as `YYYYMMDD`
+ **Data Type**: genomic
+ **Data Subtype**: mRNA, etc.
+ **Additional Variable(s):** Use 3 letter notation. For example "control" would be designated as "con". If using multiple variables, they should be separated by underscores "_".

### Examples

From the following file name, we know exactly what this file contains.

OOI-20200730-genomic-mRNA-con.fastq

+ Sample was from OOI lab
+ File generated on 7/30/2020
+ Genomic data
+ mRNA sequencing
+ From control sample
+ fastq file

## Data Standards

### Level 1

### Level 2
.bam - sorted, index file

