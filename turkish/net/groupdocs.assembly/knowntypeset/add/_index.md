---
title: "Ekle"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Belirtilen Type nesnesini kümeye ekler."
type: docs
weight: 20
url: /tr/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Belirtilen Type nesnesini kümeye ekler.

Aşağıdaki durumlarda ArgumentException fırlatır:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | Tür | Eklenecek bir Type nesnesi. |

### Ayrıca Bakınız

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
