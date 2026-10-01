---
title: "UseReflectionOptimization"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Özel tip üyelerinin yansıma API'si üzerinden yapılan çağrılarının dinamik sınıf oluşturma kullanılarak optimize edilip edilmediğini gösteren bir değeri alır veya ayarlar. Varsayılan değer true'dur."
type: docs
weight: 60
url: /tr/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Özel tip üyelerinin yansıma API'si üzerinden yapılan çağrılarının dinamik sınıf oluşturma kullanılarak optimize edilip edilmediğini gösteren bir değeri alır veya ayarlar. Varsayılan değer true'dur.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Açıklamalar

Bu optimizasyonu devre dışı bırakmanın tercih edildiği bazı senaryolar vardır. Örneğin, sürekli olarak küçük veri öğesi koleksiyonlarıyla çalışıyorsanız, dinamik sınıf oluşturmanın getirdiği ek yük, doğrudan yansıma API çağrılarının getirdiği ek yüke göre daha belirgin olabilir.

### Ayrıca Bakınız

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
