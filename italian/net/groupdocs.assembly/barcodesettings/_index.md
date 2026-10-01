---
title: "BarcodeSettings"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Rappresenta un insieme di impostazioni che controllano la generazione di codici a barre durante l'assemblaggio di un documento."
type: docs
weight: 10
url: /it/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

Rappresenta un insieme di impostazioni che controllano la generazione di codici a barre durante l'assemblaggio di un documento.

```csharp
public class BarcodeSettings
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | Ottiene o imposta la dimensione x di base, cioè la larghezza minima dell'unità delle barre e spazi del codice a barre. Misurata in [`GraphicsUnit`](./graphicsunit). |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | Ottiene o imposta la dimensione y di base, cioè l'altezza minima dell'unità dei moduli del codice a barre 2D. Misurata in [`GraphicsUnit`](./graphicsunit). |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | Ottiene o imposta un'unità grafica usata per misurare [`BaseXDimension`](./basexdimension) e [`BaseYDimension`](./baseydimension). Il valore predefinito è Millimeter. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale e verticale di un'immagine di codice a barre in generazione. Misurata in punti per pollice. Il valore predefinito è 96. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | Ottiene o imposta un valore che indica se un valore di codice a barre non valido deve essere corretto automaticamente (se possibile) per conformarsi alla specifica del codice a barre o se deve essere generata un'eccezione per indicare l'errore. Il valore predefinito è true. |

### Vedi anche

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
