---
title: ExactDateTimeParseFormats
second_title: Riferimento API GroupDocs.Assembly per .NET
description: Ottiene o imposta i formati esatti per lanalisi dei valori dataora JSON durante il caricamento di JSON. Limpostazione predefinita ènullo .
type: docs
weight: 30
url: /it/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

Ottiene o imposta i formati esatti per l'analisi dei valori data-ora JSON durante il caricamento di JSON. L'impostazione predefinita è**nullo** .

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Osservazioni

Le stringhe codificate utilizzando il formato data-ora Microsoft® JSON (ad esempio, "/Date(1224043200000)/") sono sempre riconosciute come valori data-ora indipendentemente dal valore di questa proprietà. La proprietà definisce formati aggiuntivi da utilizzare durante l'analisi dei valori data-ora dalle stringhe nel modo seguente:

* Quando`ExactDateTimeParseFormats` È**nullo** il formato ISO-8601 e tutti i formati data-ora supportati per le culture correnti, inglese USA e inglese neozelandese vengono utilizzati in aggiunta nell'ordine menzionato.
* Quando`ExactDateTimeParseFormats` contiene stringhe, vengono utilizzate come formati data-ora aggiuntivi utilizzando la cultura corrente.
* Quando`ExactDateTimeParseFormats` è vuoto, non vengono utilizzati formati data-ora aggiuntivi.

### Guarda anche

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* spazio dei nomi [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assemblea [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
