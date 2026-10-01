---
title: "JsonSimpleValueParseMode"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "JSON yüklenirken null, boolean, sayı, tamsayı ve string gibi JSON basit değerlerini ayrıştırmak için bir mod belirtir. Bu mod tarih‑zaman değerlerinin ayrıştırılmasını etkilemez."
type: docs
weight: 240
url: /tr/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

JSON yüklenirken JSON basit değerlerini (null, boolean, sayı, tam sayı ve dize) ayrıştırmak için bir mod belirtir. Böyle bir mod tarih‑zaman değerlerinin ayrıştırılmasını etkilemez.

```csharp
public enum JsonSimpleValueParseMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Loose | `0` | JSON basit değerlerinin tiplerinin, string temsilleri ayrıştırıldığında belirlendiği modu belirtir. Örneğin, '{ prop: "123" }' JSON kesitindeki 'prop' değeri bu modda tamsayı olarak belirlenir. |
| Strict | `1` | JSON basit değerlerinin tiplerinin, doğrudan JSON gösteriminden belirlendiği modu belirtir. Örneğin, '{ prop: "123" }' JSON kesitindeki 'prop' değeri bu modda string olarak belirlenir. |

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
