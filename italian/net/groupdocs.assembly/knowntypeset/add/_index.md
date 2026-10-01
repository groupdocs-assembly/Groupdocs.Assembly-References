---
title: "Add"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Aggiunge l'oggetto Type specificato all'insieme."
type: docs
weight: 20
url: /it/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Aggiunge l'oggetto Type specificato all'insieme.

Genera ArgumentException nei seguenti casi:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | Tipo | Un oggetto Type da aggiungere. |

### Vedi anche

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
