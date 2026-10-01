---
title: "Nombre"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece el nombre de esta tabla utilizado para acceder a los datos de la tabla en un documento plantilla pasado a DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 40
url: /es/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

Obtiene o establece el nombre de esta tabla utilizado para acceder a los datos de la tabla en un documento plantilla pasado a [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Observaciones

Si el nombre de la tabla se lee de un documento, el nombre se corrige automáticamente para que sea válido. Sin embargo, si el nombre de la tabla se establece manualmente mediante esta propiedad y el nombre no es válido, se lanza una excepción.

El nombre de la tabla se considera válido si se cumplen las siguientes condiciones:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### Ver también

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
