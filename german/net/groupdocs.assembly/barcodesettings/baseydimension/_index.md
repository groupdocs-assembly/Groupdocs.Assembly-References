---
title: "BaseYDimension"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Ruft die Basis‑Y‑Dimension ab oder legt sie fest, die die kleinste Höhe der Einheit von 2D‑Barcode‑Modulen ist. Gemessen in GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit."
type: docs
weight: 20
url: /de/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

Ruft die Basis‑Y‑Dimension ab oder legt sie fest, das ist die kleinste Höhe der Einheit von 2D‑Barcode‑Modulen. Gemessen in [`GraphicsUnit`](../graphicsunit).

```csharp
public float BaseYDimension { get; set; }
```

### Hinweise

Barcodes einiger Typen (wie Data Matrix) können die Y‑Dimension ignorieren und stattdessen die X‑Dimension für Breiten‑ und Höhen‑Einheiten verwenden.

Wenn die Barcode‑Skalierung über eine Vorlage angewendet wird, wird eine tatsächliche Y‑Dimension basierend auf der Basis‑Y‑Dimension und einem Skalierungsfaktor berechnet.

### Siehe auch

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
