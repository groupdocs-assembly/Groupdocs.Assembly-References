---
title: Add
second_title: Riferimento API GroupDocs.Assembly per .NET
description: Aggiunge lelemento specificatoType opporsi al set.
type: docs
weight: 20
url: /it/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Aggiunge l'elemento specificatoType opporsi al set.

GettaArgumentException nei seguenti casi:

-*type* è zero.

-*type* rappresenta un tipo vuoto.

-*type* rappresenta un tipo invisibile, ovvero un tipo non pubblico o un tipo annidato pubblico che ha un tipo esterno non pubblico.

-*type* rappresenta un tipo generico.

-*type* rappresenta un tipo di matrice.

-*type* è già stato aggiunto al set.

```csharp
public void Add(Type type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | Type | UNType oggetto da aggiungere. |

### Guarda anche

* class [KnownTypeSet](../../knowntypeset)
* spazio dei nomi [GroupDocs.Assembly](../../knowntypeset)
* assemblea [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
