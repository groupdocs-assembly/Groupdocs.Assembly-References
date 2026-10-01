---
title: "DocumentAssembler"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Şablon belgeleri verilerle doldurmak ve bu rutinleri kontrol etmek için bir dizi ayar sağlamak için rutinler sunar."
type: docs
weight: 40
url: /tr/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

Şablon belgeleri verilerle doldurmak ve bu rutinleri kontrol etmek için bir dizi ayar sağlamak için rutinler sunar.

```csharp
public class DocumentAssembler
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DocumentAssembler](documentassembler)() | Bu sınıfın yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | Bir belge birleştirirken barkod oluşturmayı kontrol eden bir ayar kümesini alır. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | Tam veya kısmi nitelikli adların bu birleştirici örneği tarafından işlenen belge şablonları içinde kullanılabileceği, ilgili tiplerin statik üyelerini çağırmak, tip dönüşümleri yapmak vb. için Type nesnelerini içeren sırasız bir küme (yani benzersiz öğeler koleksiyonu) alır. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | Bir belge birleştirirken bu [`DocumentAssembler`](../documentassembler) örneğinin davranışını kontrol eden bayrak kümesini alır veya ayarlar. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | Özel tip üyelerinin yansıma API'si üzerinden yapılan çağrılarının dinamik sınıf oluşturma kullanılarak optimize edilip edilmediğini gösteren bir değeri alır veya ayarlar. Varsayılan değer true'dur. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | Belirtilen kaynak akışından bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef akışa varsayılan [`LoadSaveOptions`](../loadsaveoptions) kullanarak kaydeder. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | Belirtilen kaynak yolundan bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef yola varsayılan [`LoadSaveOptions`](../loadsaveoptions) kullanarak kaydeder. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | Belirtilen kaynak akışından bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef akışa verilen [`LoadSaveOptions`](../loadsaveoptions) kullanarak kaydeder. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | Belirtilen kaynak yolundan bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef yola verilen [`LoadSaveOptions`](../loadsaveoptions) kullanarak kaydeder. |

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
