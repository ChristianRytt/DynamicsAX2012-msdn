﻿---
title: ReleaseUpdateDB60_Cust.allowNoDupCreditCardProcessorsNamedx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Cust.allowNoDupCreditCardProcessorsNamedx Upgrade Script
ms:assetid: 3f4ea80c-79fd-ce57-9d49-ad86f30b460b
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718781(v=AX.60)
ms:contentKeyID: 49707816
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Cust.allowNoDupCreditCardProcessorsNamedx Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Cust</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupCreditCardProcessorsNamedx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the &lt;c&gt;Name&lt;/c&gt; index of the &lt;c&gt;CreditCardProcessors&lt;/c&gt; table to not allow duplicate records.</p></td>
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
<td><p>Accounts receivable</p></td>
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
<td><p>CreditCardProcessors</p></td>
</tr>
</tbody>
</table>


## Remarks

Turn uniqueness for this index back on now that the new \<c\>Name\</c\> field has been populated.

  


