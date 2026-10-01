---
title: "Nombre"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece el nombre de esta columna usado para acceder a los datos de la columna en un documento plantilla pasado a DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 30
url: /es/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

Obtiene o establece el nombre de esta columna usado para acceder a los datos de la columna en un documento plantilla pasado a [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Observaciones

Si el nombre de la columna se lee de un documento (ver [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames)), el nombre se corrige automáticamente para que sea válido. Sin embargo, si el nombre de la columna se establece manualmente a través de esta propiedad y el nombre es inválido, se lanza una excepción.

Se considera que el nombre de la columna es válido si se cumplen las siguientes condiciones:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### Ver también

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
