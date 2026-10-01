---
title: "BarcodeSettings"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt einen Satz von Einstellungen dar, die die Barcode‑Erstellung beim Zusammenstellen eines Dokuments steuern."
type: docs
weight: 10
url: /de/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

Stellt einen Satz von Einstellungen dar, die die Barcode‑Erstellung beim Zusammenstellen eines Dokuments steuern.

```csharp
public class BarcodeSettings
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | Liest oder setzt die Basis‑x‑Dimension, also die kleinste Breite der Einheit von Strich‑ und Lückenbalken des Barcodes. Gemessen in [`GraphicsUnit`](./graphicsunit). |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | Liest oder setzt die Basis‑y‑Dimension, also die kleinste Höhe der Einheit von 2D‑Barcode‑Modulen. Gemessen in [`GraphicsUnit`](./graphicsunit). |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | Liest oder setzt eine Grafikeinheit, die zur Messung von [`BaseXDimension`](./basexdimension) und [`BaseYDimension`](./baseydimension) verwendet wird. Der Standardwert ist Millimeter. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | Liest oder setzt die horizontale und vertikale Auflösung eines zu erzeugenden Barcode‑Bildes. Gemessen in Punkten pro Zoll. Der Standardwert ist 96. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | Liest oder setzt einen Wert, der angibt, ob ein ungültiger Barcode‑Wert automatisch (wenn möglich) korrigiert werden soll, um der Spezifikation zu entsprechen, oder ob eine Ausnahme ausgelöst werden soll, um den Fehler anzuzeigen. Der Standardwert ist true. |

### Siehe auch

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
