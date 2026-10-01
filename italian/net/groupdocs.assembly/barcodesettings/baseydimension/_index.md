---
title: "BaseYDimension"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta una y-dimensione di base che è l'altezza minima dell'unità dei moduli del codice a barre 2D. Misurata in GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit."
type: docs
weight: 20
url: /it/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

Ottiene o imposta una y-dimensione di base, cioè l'altezza minima dell'unità dei moduli del codice a barre 2D. Misurata in [`GraphicsUnit`](../graphicsunit).

```csharp
public float BaseYDimension { get; set; }
```

### Osservazioni

I codici a barre di alcuni tipi (come il data matrix) possono ignorare una y-dimensione e utilizzare una x-dimensione per entrambe le unità di larghezza e altezza.

Quando la scala del codice a barre è applicata tramite un modello, una y-dimensione reale viene calcolata sulla base della y-dimensione di base e di un fattore di scala.

### Vedi anche

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
