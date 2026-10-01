---
title: "JsonDataLoadOptions"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "JSON verisinin ayrıştırılması için seçenekleri temsil eder."
type: docs
weight: 220
url: /tr/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

JSON verisinin ayrıştırılması için seçenekleri temsil eder.

```csharp
public class JsonDataLoadOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | Bu sınıfın yeni bir örneğini varsayılan seçeneklerle başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | Oluşturulan veri kaynağının her zaman bir JSON kök öğesi için bir nesne içerip içermeyeceğini belirten bir bayrağı alır veya ayarlar. Bir JSON kök öğesi tek bir karmaşık özellik içeriyorsa, böyle bir nesne varsayılan olarak oluşturulmaz. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | JSON yüklenirken JSON tarih‑zaman değerlerini ayrıştırmak için kesin formatları alır veya ayarlar. Varsayılan **null** değeridir. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | JSON yüklenirken JSON basit değerlerini (null, boolean, sayı, tam sayı ve string) ayrıştırmak için bir modu alır veya ayarlar. Böyle bir mod tarih‑zaman değerlerinin ayrıştırılmasını etkilemez. Varsayılan Loose'tur. |

### Açıklamalar

Bu sınıfın bir örneği, [`JsonDataSource`](../jsondatasource) yapıcılarına geçirilebilir.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
