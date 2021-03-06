﻿---
title: ReleaseUpdateDB60_HRM.updateHcmJobTaskAssignment Upgrade Script
TOCTitle: ReleaseUpdateDB60_HRM.updateHcmJobTaskAssignment Upgrade Script
ms:assetid: 6390b0fa-46b2-8f65-ab66-f418f0cd9aa9
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719136(v=AX.60)
ms:contentKeyID: 49708675
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_HRM.updateHcmJobTaskAssignment Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_HRM</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateHcmJobTaskAssignment</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Inserts data into the HcmJobTaskAssignment table from the HRMJobTask table.</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Human Resources</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>HcmJobTemplateTask</p></td>
</tr>
<tr class="even">
<td><p>HRMJobTask</p></td>
</tr>
<tr class="odd">
<td><p>HcmJob</p></td>
</tr>
<tr class="even">
<td><p>HRMTask</p></td>
</tr>
</tbody>
</table>


## Remarks

1.  The Job field which holds record ID from the HcmJob table replaces the Reference field.

2.  The JobTask field which holds record ID from the HcmJobTask table replaces the TaskId field.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: HRMJobTask</p></th>
<th><p>To Table: HcmJobTaskAssignment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>HcmJobTaskAssignment</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>HRMJobTask</p></td>
<td><p>*</p></td>
</tr>
</tbody>
</table>

  


