---
title: KSPROPERTY\_MEDIASEEKING\_POSITIONS
description: The KSPROPERTY\_MEDIASEEKING\_POSITIONS property sets the media time and/or the stop time on a filter.
keywords: ["KSPROPERTY_MEDIASEEKING_POSITIONS Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_MEDIASEEKING_POSITIONS
api_location:
- ks.h
api_type:
- HeaderDef
ms.date: 11/28/2017
ms.localizationpriority: medium
---

# KSPROPERTY\_MEDIASEEKING\_POSITIONS


The KSPROPERTY\_MEDIASEEKING\_POSITIONS property sets the media time and/or the stop time on a filter.

## <span id="ddk_ksproperty_mediaseeking_positions_ks"></span><span id="DDK_KSPROPERTY_MEDIASEEKING_POSITIONS_KS"></span>


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
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>Filter</p></td>
<td><p><a href="/windows-hardware/drivers/stream/ksproperty-structure" data-raw-source="[&lt;strong&gt;KSPROPERTY&lt;/strong&gt;](./ksproperty-structure.md)"><strong>KSPROPERTY</strong></a></p></td>
<td><p><a href="/windows-hardware/drivers/ddi/ks/ns-ks-ksproperty_positions" data-raw-source="[&lt;strong&gt;KSPROPERTY_POSITIONS&lt;/strong&gt;](/windows-hardware/drivers/ddi/ks/ns-ks-ksproperty_positions)"><strong>KSPROPERTY_POSITIONS</strong></a></p></td>
</tr>
</tbody>
</table>

 

## Remarks

The KSPROPERTY\_POSITIONS structure specifies the current position and stop position relative to the total duration of the stream.

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


[**KSPROPERTY\_POSITIONS**](/windows-hardware/drivers/ddi/ks/ns-ks-ksproperty_positions)