---
title: "Name"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Ruft den Namen dieser Spalte ab oder legt ihn fest, der verwendet wird, um auf die Spaltendaten in einem Vorlagendokument zuzugreifen, das an DocumentAssemblergroupdocs.assembly/documentassembler übergeben wird."
type: docs
weight: 30
url: /de/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

Ruft den Namen dieser Spalte ab oder legt ihn fest, der verwendet wird, um auf die Spaltendaten in einem Vorlagendokument zuzugreifen, das an [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler) übergeben wird.

```csharp
public string Name { get; set; }
```

### Hinweise

Wenn der Spaltenname aus einem Dokument gelesen wird (siehe [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames)), wird der Name automatisch korrigiert, sodass er gültig ist. Wird der Spaltenname jedoch manuell über diese Eigenschaft festgelegt und ist ungültig, wird eine Ausnahme ausgelöst.

Der Spaltenname gilt als gültig, wenn die folgenden Bedingungen erfüllt sind:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### Siehe auch

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
