---
title: "ResourceSaveFolder"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Harici kaynak dosyalarını depolamak için bir klasör yolunu alır veya ayarlar; bu, HTML dışı bir formatta yüklü birleştirilmiş belge HTML olarak kaydedilirken geçerlidir. Varsayılan değer boş bir dizedir."
type: docs
weight: 30
url: /tr/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

HTML dışı bir biçimde yüklü birleştirilmiş belge HTML'ye kaydedilirken dış kaynak dosyalarını depolamak için klasör yolunu alır veya ayarlar. Varsayılan değer boş bir dizedir.

```csharp
public string ResourceSaveFolder { get; set; }
```

### Açıklamalar

Varsayılan olarak, birleştirilmiş belge bir HTML dosyasına kaydedilirken, harici kaynak dosyaları uzantısı olmayan HTML dosyasının aynı adıyla ve \"_files\" ekini alarak bir klasöre kaydedilir. Bu klasör, HTML dosyasıyla aynı klasörde bulunur. Ancak, birleştirilmiş belge bir HTML akışına kaydedilirken bu yapılamaz. Bu özelliği, birleştirilmiş belge bir HTML akışına kaydedilirken harici kaynak dosyalarını depolamak için bir klasör yolu belirtmek veya birleştirilmiş belge bir HTML dosyasına kaydedilirken varsayılan klasörü geçersiz kılmak için ayarlayın.

Bu özelliğin değeri, HTML olarak kaydedilen birleştirilmiş belge aynı zamanda HTML'den yüklendiyse yok sayılır (harici kaynak dosyaları depolanmaz ve onlara olan bağlantılar değiştirilmez).

### Ayrıca Bakınız

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
