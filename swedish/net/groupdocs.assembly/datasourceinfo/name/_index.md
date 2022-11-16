---
title: Name
second_title: GroupDocs.Assembly för .NET API-referens
description: Hämtar eller ställer in namnet på datakällobjektet som ska användas för att komma åt datakällobjektet i ett malldokument.
type: docs
weight: 30
url: /sv/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

Hämtar eller ställer in namnet på datakällobjektet som ska användas för att komma åt datakällobjektet i ett malldokument.

```csharp
public string Name { get; set; }
```

### Anmärkningar

När namnet på datakällsobjektet anges kan du komma åt datakällobjektet och dess medlemmar i ett malldokument med namnet.

När namnet på datakällobjektet är null eller tomt, kan du fortfarande komma åt medlemmar av datakällobjektet i ett malldokument med hjälp av kontextobjektmedlemsåtkomst (se Mallsyntaxreferens för mer information), men du kan inte komma åt själva datakällans objekt.

När du passerar flera[`DataSourceInfo`](../../datasourceinfo) instanser till[`DocumentAssembler`](../../documentassembler) , endast namnet på det första datakällobjektet kan vara null eller tomt. Namnen på de övriga måste anges och unika.

### Se även

* class [DataSourceInfo](../../datasourceinfo)
* namnutrymme [GroupDocs.Assembly](../../datasourceinfo)
* hopsättning [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->