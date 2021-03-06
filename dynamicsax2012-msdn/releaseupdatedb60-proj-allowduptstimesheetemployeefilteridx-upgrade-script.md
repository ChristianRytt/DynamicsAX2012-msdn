﻿---
title: ReleaseUpdateDB60_Proj.allowDupTSTimesheetEmployeeFilterIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Proj.allowDupTSTimesheetEmployeeFilterIdx Upgrade Script
ms:assetid: 8adabeaa-fc2e-09e3-5ac7-adf51106002c
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736411(v=AX.60)
ms:contentKeyID: 49709601
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Proj.allowDupTSTimesheetEmployeeFilterIdx Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Proj</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupTSTimesheetEmployeeFilterIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the Idx index in the TSTimesheetEmployeeFilter table to allow for duplicate records.</p></td>
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
<td><p>Project</p></td>
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
<td><p>TSTimesheetEmployeeFilter</p></td>
</tr>
</tbody>
</table>


## Remarks

Initially the Worker field contains no value. So the index is set to allow for duplicates before the field is updated with the value of the record ID field in the HcmWorker table.

  


