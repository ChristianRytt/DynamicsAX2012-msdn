﻿---
title: ReleaseUpdateDB60_Ledger.allowNoDupEximIncentiveSchemeData_INInce
TOCTitle: ReleaseUpdateDB60_Ledger.allowNoDupEximIncentiveSchemeData_INInce
ms:assetid: 9a0bb503-1dad-f4b2-8d62-331dc96152f6
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686285(v=AX.60)
ms:contentKeyID: 49709988
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowNoDupEximIncentiveSchemeData\_INInce 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupEximIncentiveSchemeData_INInce</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index &lt;c&gt;IncentiveSchemeIdx&lt;/c&gt; in the table &lt;c&gt;EximIncentiveSchemeData_IN&lt;/c&gt; not to allow duplicate records.</p></td>
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
<td><p>General ledger</p></td>
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
<td><p>EXIMINCENTIVESCHEMEDATA_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the surrogate key fields EximIncentiveSchemeGroup with the value of the RecId field of the tables, the index IncentiveSchemeIdx is reset not to allow duplicate records.

  


