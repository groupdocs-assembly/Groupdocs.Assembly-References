---
title: "DocumentAssemblyOptions"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belge birleştirirken DocumentAssembler./documentassembler davranışını kontrol eden seçenekleri belirtir."
type: docs
weight: 50
url: /tr/net/groupdocs.assembly/documentassemblyoptions/
---
## DocumentAssemblyOptions enumeration

Bir belge birleştirirken [`DocumentAssembler`](../documentassembler) davranışını kontrol eden seçenekleri belirtir.

```csharp
[Flags]
public enum DocumentAssemblyOptions
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | Varsayılan seçenekleri belirtir. |
| AllowMissingMembers | `1` | Eksik nesne üyelerinin birleştirici tarafından null sabitleri olarak ele alınması gerektiğini belirtir. Bu seçenek yalnızca örnek (yani statik olmayan) nesne üyelerine ve uzantı yöntemlerine erişimi etkiler. Bu seçenek ayarlanmamışsa, birleştirici eksik bir nesne üyesiyle karşılaştığında bir istisna fırlatır. |
| UpdateFieldsAndFormulas | `2` | Birleştiricinin sonuç Word İşleme belgelerinin alanlarını ve sonuç Spreadsheet belgelerinin formüllerini güncellemesi gerektiğini belirtir. |
| RemoveEmptyParagraphs | `4` | Şablon sözdizimi etiketleri kaldırıldıktan veya boş değerlerle değiştirildikten sonra boş kalan paragrafların birleştirici tarafından kaldırılması gerektiğini belirtir. |
| InlineErrorMessages | `8` | Birleştiricinin şablon sözdizimi hata mesajlarını çıktı belgelerine satır içi eklemesi gerektiğini belirtir. Bu seçenek ayarlanmamışsa, birleştirici bir sözdizimi hatasıyla karşılaştığında bir istisna fırlatır. |
| UseSpreadsheetDataTypes | `10` | Yalnızca Spreadsheet belgeleriyle ilgilidir. Değerlendirilen ifade sonuçlarının karşılık gelen Spreadsheet veri türlerine eşlenmesi gerektiğini, bunun ayrıca hücrelerdeki varsayılan biçimlendirmeyi etkilediğini belirtir. Bu seçenek ayarlanmamışsa, ifade sonuçları her zaman birleştirici tarafından dize olarak yazılır. Bu seçenek, ifade sonuçları şablon sözdizimi kullanılarak biçimlendirildiğinde etkisizdir – bu durumda da ifade sonuçları her zaman dize olarak yazılır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
