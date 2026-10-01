---
title: "Nome"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta il nome dell'oggetto data source da utilizzare per accedere all'oggetto data source in un documento modello."
type: docs
weight: 30
url: /it/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

Ottiene o imposta il nome dell'oggetto data source da utilizzare per accedere all'oggetto data source in un documento modello.

```csharp
public string Name { get; set; }
```

### Osservazioni

Quando il nome dell'oggetto data source è specificato, è possibile accedere all'oggetto data source e ai suoi membri in un documento modello utilizzando il nome.

Quando il nome dell'oggetto data source è null o vuoto, è comunque possibile accedere ai membri dell'oggetto data source in un documento modello utilizzando l'accesso ai membri dell'oggetto contesto (vedi Riferimento alla sintassi del modello per ulteriori informazioni), ma non è possibile accedere all'oggetto data source stesso.

Quando si passano più istanze di [`DataSourceInfo`](../../datasourceinfo) a [`DocumentAssembler`](../../documentassembler), solo il nome del primo oggetto data source può essere null o vuoto. I nomi degli altri devono essere specificati e unici.

### Vedi anche

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
