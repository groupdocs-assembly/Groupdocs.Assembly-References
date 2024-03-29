---
title: BarcodeSettings
second_title: .NET API Başvurusu için GroupDocs.Assembly
description: Bir belgeyi bir araya getirirken barkod oluşturmayı kontrol eden bir dizi ayarı temsil eder.
type: docs
weight: 10
url: /tr/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

Bir belgeyi bir araya getirirken barkod oluşturmayı kontrol eden bir dizi ayarı temsil eder.

```csharp
public class BarcodeSettings
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | Temel x boyutunu, yani barkod çubukları ve boşluk biriminin en küçük genişliğini alır veya ayarlar. Ölçülen[`GraphicsUnit`](./graphicsunit) . |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | Temel y boyutunu, yani 2B barkod modüllerinin biriminin en küçük yüksekliğini alır veya ayarlar. Ölçülen[`GraphicsUnit`](./graphicsunit) . |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | Ölçmek için kullanılan bir grafik birimini alır veya ayarlar[`BaseXDimension`](./basexdimension) Ve[`BaseYDimension`](./baseydimension) . Varsayılan değer:Millimeter . |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | Oluşturulan bir barkod görüntüsünün yatay ve dikey çözünürlüğünü alır veya ayarlar. İnç başına dots cinsinden ölçülmüştür. Varsayılan değer 96. 'dir. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | Geçersiz bir barkod değerinin barkodun özelliklerine uyması için otomatik olarak (mümkünse) düzeltilmesi veya hatayı belirtmek için bir istisna atılması gerekip gerekmediğini gösteren bir değer alır veya ayarlar. Varsayılan değer true'dur. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Assembly](../../groupdocs.assembly)
* toplantı [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
