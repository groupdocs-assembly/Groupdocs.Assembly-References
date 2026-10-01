---
title: "Ad"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Şablon belgesinde veri kaynağı nesnesine erişmek için kullanılacak veri kaynağı nesnesinin adını alır veya ayarlar."
type: docs
weight: 30
url: /tr/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

Şablon belgesinde veri kaynağı nesnesine erişmek için kullanılacak veri kaynağı nesnesinin adını alır veya ayarlar.

```csharp
public string Name { get; set; }
```

### Açıklamalar

Veri kaynağı nesnesinin adı belirtildiğinde, şablon belgesinde veri kaynağı nesnesine ve üyelerine adı kullanarak erişebilirsiniz.

Veri kaynağı nesnesinin adı null veya boş olduğunda, şablon belgesinde bağlam nesnesi üye erişimini kullanarak (daha fazla bilgi için Template Syntax Reference bölümüne bakın) yine de veri kaynağı nesnesinin üyelerine erişebilirsiniz, ancak veri kaynağı nesnesine doğrudan erişemezsiniz.

Birden fazla [`DataSourceInfo`](../../datasourceinfo) örneğini [`DocumentAssembler`](../../documentassembler)'a gönderirken, yalnızca ilk veri kaynağı nesnesinin adı null veya boş olabilir. Diğerlerinin adları belirtilmeli ve benzersiz olmalıdır.

### Ayrıca Bakınız

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
