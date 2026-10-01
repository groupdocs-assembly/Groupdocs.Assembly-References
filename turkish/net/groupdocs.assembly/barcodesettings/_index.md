---
title: "BarcodeSettings"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belge birleştirirken barkod oluşturmayı kontrol eden ayarların bir kümesini temsil eder."
type: docs
weight: 10
url: /tr/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

Bir belge birleştirirken barkod oluşturmayı kontrol eden ayarların bir kümesini temsil eder.

```csharp
public class BarcodeSettings
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | Temel x-boyutunu alır veya ayarlar; yani barkod çubukları ve boşluk biriminin en küçük genişliği. [`GraphicsUnit`](./graphicsunit) cinsinden ölçülür. |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | Temel y-boyutunu alır veya ayarlar; yani 2D barkod modüllerinin birim yüksekliğinin en küçüğü. [`GraphicsUnit`](./graphicsunit) cinsinden ölçülür. |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | [`BaseXDimension`](./basexdimension) ve [`BaseYDimension`](./baseydimension) ölçümünde kullanılan grafik birimini alır veya ayarlar. Varsayılan değer Milimetre'dir. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | Oluşturulan barkod görüntüsünün yatay ve dikey çözünürlüğünü alır veya ayarlar. İnç başına nokta (dpi) cinsinden ölçülür. Varsayılan değer 96'dır. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | Geçersiz bir barkod değerinin barkodun spesifikasyonuna uyması için otomatik olarak (mümkünse) düzeltilip düzeltilmeyeceğini veya hatayı göstermek için bir istisna fırlatılıp fırlatılmayacağını belirten bir değeri alır veya ayarlar. Varsayılan değer true'dur. |

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
