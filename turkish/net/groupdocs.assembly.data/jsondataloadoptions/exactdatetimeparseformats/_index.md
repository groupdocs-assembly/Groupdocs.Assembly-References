---
title: "ExactDateTimeParseFormats"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "JSON yüklenirken JSON datetime değerlerini ayrıştırmak için kesin formatları alır veya ayarlar. Varsayılan null."
type: docs
weight: 30
url: /tr/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

JSON yüklenirken JSON tarih‑zaman değerlerini ayrıştırmak için kesin formatları alır veya ayarlar. Varsayılan **null** değeridir.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Açıklamalar

Microsoft® JSON tarih-zaman formatı kullanılarak kodlanmış dizeler (örneğin, "/Date(1224043200000)/") bu özelliğin değerine bakılmaksızın her zaman tarih-zaman değeri olarak tanınır. Özellik, dizelerden tarih-zaman değerlerini ayrıştırırken aşağıdaki şekilde kullanılacak ek formatları tanımlar:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### Ayrıca Bakınız

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
