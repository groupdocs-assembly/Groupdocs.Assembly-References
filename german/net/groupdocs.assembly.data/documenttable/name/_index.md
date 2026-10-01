---
title: "Name"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder setzt den Namen dieser Tabelle, die verwendet wird, um auf die Tabellendaten in einem Vorlagendokument zuzugreifen, das an DocumentAssemblergroupdocs.assembly/documentassembler übergeben wird."
type: docs
weight: 40
url: /de/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

Liest oder setzt den Namen dieser Tabelle, die verwendet wird, um auf die Tabellendaten in einem Vorlagendokument zuzugreifen, das an [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler) übergeben wird.

```csharp
public string Name { get; set; }
```

### Hinweise

Wenn der Tabellenname aus einem Dokument gelesen wird, wird der Name automatisch korrigiert, sodass er gültig ist. Wird der Tabellenname jedoch manuell über diese Eigenschaft gesetzt und ist der Name ungültig, wird eine Ausnahme ausgelöst.

Der Tabellenname gilt als gültig, wenn die folgenden Bedingungen erfüllt sind:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### Siehe auch

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
