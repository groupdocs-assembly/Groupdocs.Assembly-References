---
title: "UseReflectionOptimization"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta un valore che indica se le invocazioni dei membri di tipo personalizzato eseguite tramite l'API di riflessione sono ottimizzate mediante generazione dinamica di classi o meno. Il valore predefinito è true."
type: docs
weight: 60
url: /it/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Ottiene o imposta un valore che indica se le invocazioni dei membri di tipo personalizzato eseguite tramite l'API di riflessione sono ottimizzate mediante generazione dinamica di classi o meno. Il valore predefinito è true.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Osservazioni

Ci sono alcuni scenari in cui è preferibile disabilitare questa ottimizzazione. Ad esempio, se si lavora continuamente con piccole collezioni di elementi dati, allora un overhead di generazione dinamica di classi può risultare più evidente rispetto a un overhead di chiamate dirette all'API di reflection.

### Vedi anche

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
