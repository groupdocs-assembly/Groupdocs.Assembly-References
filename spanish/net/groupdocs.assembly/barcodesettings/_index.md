---
title: "BarcodeSettings"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Representa un conjunto de configuraciones que controlan la generación de códigos de barras al ensamblar un documento."
type: docs
weight: 10
url: /es/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

Representa un conjunto de configuraciones que controlan la generación de códigos de barras al ensamblar un documento.

```csharp
public class BarcodeSettings
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | Obtiene o establece una dimensión x base, es decir, el ancho más pequeño de la unidad de barras y espacios del código de barras. Medido en [`GraphicsUnit`](./graphicsunit). |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | Obtiene o establece una dimensión y base, es decir, la altura más pequeña de la unidad de módulos de código de barras 2D. Medido en [`GraphicsUnit`](./graphicsunit). |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | Obtiene o establece una unidad gráfica utilizada para medir [`BaseXDimension`](./basexdimension) y [`BaseYDimension`](./baseydimension). El valor predeterminado es Millimeter. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | Obtiene o establece la resolución horizontal y vertical de una imagen de código de barras que se está generando. Medido en puntos por pulgada. El valor predeterminado es 96. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | Obtiene o establece un valor que indica si un valor de código de barras inválido debe corregirse automáticamente (si es posible) para ajustarse a la especificación del código de barras o si se debe lanzar una excepción para indicar el error. El valor predeterminado es true. |

### Ver también

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
