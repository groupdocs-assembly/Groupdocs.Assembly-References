---
title: "BaseYDimension"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "2D barkod modüllerinin birim yüksekliğinin en küçük olduğu temel y-dimensiyonunu alır veya ayarlar. GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit içinde ölçülür."
type: docs
weight: 20
url: /tr/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

2D barkod modüllerinin birim yüksekliğinin en küçük olduğu temel y-dimensiyonunu alır veya ayarlar. [`GraphicsUnit`](../graphicsunit) biriminde ölçülür.

```csharp
public float BaseYDimension { get; set; }
```

### Açıklamalar

Bazı tip barkodlar (ör. data matrix) y-dimensiyonu göz ardı edip hem genişlik hem de yükseklik birimleri için x-dimensiyonu kullanabilir.

Bir şablon aracılığıyla barkod ölçeklendirmesi uygulandığında, temel y-dimensiyon ve bir ölçek faktörü üzerine gerçek bir y-dimensiyon hesaplanır.

### Ayrıca Bakınız

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
