---
title: "Add"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Agrega el objeto Type especificado al conjunto."
type: docs
weight: 20
url: /es/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Agrega el objeto Type especificado al conjunto.

Lanza ArgumentException en los siguientes casos:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| type | Type | Un objeto Type para agregar. |

### Ver también

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
