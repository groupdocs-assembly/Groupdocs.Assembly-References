---
title: UseReflectionOptimization
second_title: .NET API Başvurusu için GroupDocs.Assembly
description: Yansıma APIsi aracılığıyla gerçekleştirilen özel tür üyelerinin çağrılarının dinamik sınıf oluşturma kullanılarak optimize edilip edilmediğini gösteren bir değer alır veya ayarlar. Varsayılan değer true.
type: docs
weight: 60
url: /tr/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Yansıma API'si aracılığıyla gerçekleştirilen özel tür üyelerinin çağrılarının dinamik sınıf oluşturma kullanılarak optimize edilip edilmediğini gösteren bir değer alır veya ayarlar. Varsayılan değer true.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Notlar

Bu optimizasyonu devre dışı bırakmanın tercih edildiği bazı senaryolar vardır. Örneğin, her zaman küçük veri öğeleri koleksiyonlarıyla uğraşıyorsanız, dinamik sınıf oluşturma ek yükü, doğrudan yansıma API çağrılarının ek yükünden daha fazla fark edilebilir olabilir.

### Ayrıca bakınız

* class [DocumentAssembler](../../documentassembler)
* ad alanı [GroupDocs.Assembly](../../documentassembler)
* toplantı [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->