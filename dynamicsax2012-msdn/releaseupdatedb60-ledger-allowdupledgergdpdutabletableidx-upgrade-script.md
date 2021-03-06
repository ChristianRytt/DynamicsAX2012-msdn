﻿---
title: ReleaseUpdateDB60_Ledger.allowDupLedgerGDPdUTableTableIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupLedgerGDPdUTableTableIdx Upgrade Script
ms:assetid: b64a41f4-0854-98f1-60e8-bedde79fb435
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737016(v=AX.60)
ms:contentKeyID: 49710698
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupLedgerGDPdUTableTableIdx Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

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
<td><p>allowDupLedgerGDPdUTableTableIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the TableIdx index in the LedgerGDPdUTable table to allow for duplicate records.</p></td>
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
<td><p>LedgerGDPdUTable</p></td>
</tr>
</tbody>
</table>


## Remarks

The GDPdUGroupId field is replaced with the new LedgerGDPdUGroup surrogate key field in the unique TableIdx index. Initially, this field contains no value. Therefore, the index is set to allow for duplicate values before the field is updated with the value of the RecId field of the LedgerGDPdUGroup table.

  


