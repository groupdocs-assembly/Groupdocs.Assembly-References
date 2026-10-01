---
title: "BaseYDimension"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece una dimensión y base que es la altura más pequeña de la unidad de módulos del código de barras 2D. Medido en GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit."
type: docs
weight: 20
url: /es/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

Obtiene o establece una dimensión y base, es decir, la altura más pequeña de la unidad de módulos del código de barras 2D. Medido en [`GraphicsUnit`](../graphicsunit).

```csharp
public float BaseYDimension { get; set; }
```

### Observaciones

Los códigos de barras de algunos tipos (como data matrix) pueden ignorar una dimensión y usar una dimensión x para ambas unidades de ancho y altura.

Cuando se aplica el escalado del código de barras a través de una plantilla, se calcula una dimensión y real a partir de la dimensión y base y un factor de escala.

### Ver también

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
