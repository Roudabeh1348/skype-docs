﻿---
title: Trunk element (QualityEndPointType complexType) 
TOCTitle: Trunk element (QualityEndPointType complexType)
ms:assetid: 748b3e24-cbaf-18d6-ad8e-5ece4e69caea
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171010(v=office.16)
ms:contentKeyID: 65855583
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Trunk element (QualityEndPointType complexType) (Schema D)

(QualityEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Identifier for the SipTrunk or other SIP device used to connect to the endpoint.


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:string</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="Trunk"  type="xs:string" minOccurs="0">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col />
<col />
<col />
</colgroup>
<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="from-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">From</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
<td><p>The source of the reported media stream.</p></td>
</tr>
<tr class="even">
<td><p><a href="to-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">To</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
<td><p>Destination of the media stream.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

