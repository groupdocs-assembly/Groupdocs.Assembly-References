---
title: "SaveFormat"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Birleştirilmiş belgeyi kaydetmek için dosya biçimini alır veya ayarlar. Belirtilmemişse varsayılan değerdir."
type: docs
weight: 40
url: /tr/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

Birleştirilmiş belgeyi kaydetmek için dosya biçimini alır veya ayarlar. Belirtilmemişse varsayılan değerdir.

```csharp
public FileFormat SaveFormat { get; set; }
```

### Açıklamalar

Bu özelliğin değeri belirtilmediğinde, [`DocumentAssembler`](../../documentassembler) aşağıdaki şekilde davranır:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

GroupDocs.Assembly kullanarak birleştirilmiş bir belgeyi herhangi bir dosya formatına kaydetmenin her zaman mümkün olmadığını unutmayın. Örneğin, bir Word İşleme dosya formatından (ör. DOCX) yüklenen bir belgeyi bir Elektronik Tablo dosya formatına (ör. XLSX) kaydetmek mümkün değildir. GroupDocs.Assembly tarafından desteklenen yükleme ve kaydetme dosya formatı kombinasyonları hakkında daha fazla bilgi için lütfen GroupDocs.Assembly çevrimiçi belgelerine bakın.

### Ayrıca Bakınız

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
