﻿---
title: ReleaseUpdateDB60_Jmg.allowNoDupJmgPayAgreementOverrideEmplDat Upgrade Script
TOCTitle: ReleaseUpdateDB60_Jmg.allowNoDupJmgPayAgreementOverrideEmplDat Upgrade Script
ms:assetid: aacafd45-d890-7a4a-3682-face3e319dff
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686459(v=AX.60)
ms:contentKeyID: 49710413
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Jmg.allowNoDupJmgPayAgreementOverrideEmplDat Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Jmg</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupJmgPayAgreementOverrideEmplDat</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the EmplDateIdx index in the JmgPayAgreementOverride table not to allow for duplicate records.</p></td>
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
<td><p>Shop Floor Control</p></td>
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
<td><p>JmgPayAgreementOverride</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the Worker surrogate key field with the value of the RecId field of the HcmWorker table, the EmplDateIdx index is reset not to allow for duplicate records.

  


