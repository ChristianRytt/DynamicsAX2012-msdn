﻿---
title: ReleaseUpdateDB60_HRM.updateHcmi9Document
TOCTitle: ReleaseUpdateDB60_HRM.updateHcmi9Document
ms:assetid: 8e54fb7e-7502-14fe-8e83-5232b55177cb
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736504(v=AX.60)
ms:contentKeyID: 49709693
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_HRM.updateHcmi9Document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

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
<td><p>updateHcmi9Document</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Inserts records into the &lt;c&gt;Hcmi9Document&lt;/c&gt; table from the &lt;c&gt;HRMi9Document&lt;/c&gt; table.</p></td>
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
<td><p>CompanyInfo</p></td>
</tr>
<tr class="even">
<td><p>EmplTable</p></td>
</tr>
<tr class="odd">
<td><p>Hcmi9Document</p></td>
</tr>
<tr class="even">
<td><p>HcmWorker</p></td>
</tr>
<tr class="odd">
<td><p>HCMWorkerAffiliation</p></td>
</tr>
<tr class="even">
<td><p>HRMi9Document</p></td>
</tr>
<tr class="odd">
<td><p>HRMi9DocumentType</p></td>
</tr>
<tr class="even">
<td><p>LogisticsAddressZipCode</p></td>
</tr>
</tbody>
</table>


## Remarks

This upgrade will retain the data of each company. The \<c\>EmployeeAffiliation\</c\> field in the \<c\>\</c\> table is the foreign key to the \<c\>HcmEmployeeAffiliation\</c\> table. The \<c\>VerifiedBy\</c\> field in the \<c\>\</c\> table is the foreign key to the \<c\>HcmWorker\</c\> table. The \<c\>PreparerZipCode\</c\> field in the \<c\>\</c\> table is the foreign key to the \<c\>LogisticsAddressZipCode\</c\> table.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: HRMi9Document</p></th>
<th><p>To Table: Hcmi9Document</p></th>
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
<td><p>Hcmi9Document</p></td>
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
<td><p>HRMi9Document</p></td>
<td><p>*</p></td>
</tr>
</tbody>
</table>

  


