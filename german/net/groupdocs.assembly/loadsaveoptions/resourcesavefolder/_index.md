---
title: "ResourceSaveFolder"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder legt einen Pfad zu einem Ordner fest, in dem externe Ressourcendateien gespeichert werden, während ein zusammengesetztes Dokument, das aus einem Nicht-HTML-Format geladen wurde, nach HTML gespeichert wird. Der Standardwert ist eine leere Zeichenfolge."
type: docs
weight: 30
url: /de/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

Liest oder setzt einen Pfad zu einem Ordner, in dem externe Ressourcendateien gespeichert werden, während ein aus einem Nicht‑HTML‑Format geladenes zusammengefügtes Dokument nach HTML gespeichert wird. Der Standardwert ist eine leere Zeichenkette.

```csharp
public string ResourceSaveFolder { get; set; }
```

### Hinweise

Standardmäßig werden beim Speichern eines zusammengesetzten Dokuments in einer HTML-Datei externe Ressourcendateien in einem Ordner abgelegt, dessen Name dem Namen der HTML-Datei ohne Erweiterung plus dem Suffix "_files" entspricht. Dieser Ordner befindet sich im selben Verzeichnis wie die HTML-Datei. Dies kann jedoch nicht durchgeführt werden, wenn ein zusammengesetztes Dokument in einen HTML-Stream gespeichert wird. Setzen Sie diese Eigenschaft, um einen Pfad zu einem Ordner anzugeben, in dem externe Ressourcendateien beim Speichern eines zusammengesetzten Dokuments in einen HTML-Stream gespeichert werden sollen, oder um den Standardordner beim Speichern eines zusammengesetzten Dokuments in einer HTML-Datei zu überschreiben.

Ein Wert dieser Eigenschaft wird ignoriert, wenn ein zusammengesetztes Dokument, das nach HTML gespeichert wird, ebenfalls aus HTML geladen wurde (externe Ressourcendateien werden dann nicht gespeichert und die Links zu ihnen werden nicht geändert).

### Siehe auch

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
