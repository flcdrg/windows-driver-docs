---
title: KSPROPERTY\_CLOCK\_STATE
description: Clients use the KSPROPERTY\_CLOCK\_STATE property to determine the streaming state of a pin.
keywords: ["KSPROPERTY_CLOCK_STATE Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_CLOCK_STATE
api_location:
- ks.h
api_type:
- HeaderDef
ms.date: 11/28/2017
ms.localizationpriority: medium
---

# KSPROPERTY\_CLOCK\_STATE


Clients use the KSPROPERTY\_CLOCK\_STATE property to determine the streaming state of a pin.

## <span id="ddk_ksproperty_clock_state_ks"></span><span id="DDK_KSPROPERTY_CLOCK_STATE_KS"></span>


### Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property Descriptor Type</th>
<th>Property Value Type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Pin</p></td>
<td><p><a href="/windows-hardware/drivers/stream/ksproperty-structure" data-raw-source="[&lt;strong&gt;KSPROPERTY&lt;/strong&gt;](./ksproperty-structure.md)"><strong>KSPROPERTY</strong></a></p></td>
<td><p><a href="/windows-hardware/drivers/ddi/ks/ne-ks-ksstate" data-raw-source="[&lt;strong&gt;KSSTATE&lt;/strong&gt;](/windows-hardware/drivers/ddi/ks/ne-ks-ksstate)"><strong>KSSTATE</strong></a></p></td>
</tr>
</tbody>
</table>

 

## Remarks

Also see [KS Properties](./ks-properties.md).

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ks.h (include Ks.h)</td>
</tr>
</tbody>
</table>

## See also


[**KSSTATE**](/windows-hardware/drivers/ddi/ks/ne-ks-ksstate)