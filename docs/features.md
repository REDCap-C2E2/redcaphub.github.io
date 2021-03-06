---
layout: default
title: New Features
nav_order: 5
---

# New Features
{: .no_toc }

All of the new REDCap features that have been rolled out in the most recent versions explained in depth, with details on how to set them up, work with them and get the most out.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## REDCap v10.0
{: .d-inline-block }

Newest Release
{: .label .label-green }

### Field Embedding

Field Embedding allows you to reposition field elements on a survey page or data entry form so that they get embedded in a new location on that same page. Embedding fields gives users greater control over the look and feel of your instrument. Users may place fields in a grid/table for a more compact user-friendly page, or they can position fields close together in a group if they are related.

### Stealth Queue

This setting will keep the Survey Queue table hidden from participants, and will force Auto Start to be enabled for all queue-activated surveys. This is useful if users wish to use the Survey Queue to automatically guide survey participants to the next survey without displaying the queue of surveys.

### New action tag: @CALCDATE

Performs a date calculation by adding or subtracting a specified amount of time from a specified date or datetime field and then provides the result as a date or datetime value - e.g. `@CALCDATE([visit_date], 7, 'd')`.

### New action tag: @CALCTEXT

Evaluates logic that is provided inside a `@CALCTEXT()` function and outputs the result as text, typically performed with an if(x,y,z) function - e.g. `@CALCTEXT(if([gender]='1', 'male', 'female'))`.

## REDCap v9.5

### Alerts & Notifications

The feature allows you to construct alerts and send customized email notifications.


### Missing Data Codes

Fields that have a blank/missing value may be marked with a custom `Missing Data Code` to note why the value is blank.

### File Version History

File Upload fields (project-level setting) - The feature allows you to upload a new file to the File Upload field, without deleting the current file in the field. This feature will keep a track of different versions of an uploaded file within the data history popup which is a table that contains all versions of the file.
