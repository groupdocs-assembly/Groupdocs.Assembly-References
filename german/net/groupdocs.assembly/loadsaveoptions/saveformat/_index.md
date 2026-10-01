---
title: "SaveFormat"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder setzt ein Dateiformat, in dem ein zusammengefügtes Dokument gespeichert wird. Nicht angegeben ist der Standardwert."
type: docs
weight: 40
url: /de/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

Liest oder setzt ein Dateiformat, in dem ein zusammengefügtes Dokument gespeichert wird. Nicht angegeben ist der Standardwert.

```csharp
public FileFormat SaveFormat { get; set; }
```

### Hinweise

Wenn der Wert dieser Eigenschaft nicht angegeben ist, verhält sich [`DocumentAssembler`](../../documentassembler) wie folgt:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

Beachten Sie, dass es nicht immer möglich ist, ein zusammengesetztes Dokument mit GroupDocs.Assembly in ein beliebiges Dateiformat zu speichern. Beispielsweise ist es unmöglich, ein aus einem Textverarbeitungsformat (wie DOCX) geladenes Dokument in ein Tabellenkalkulationsformat (wie XLSX) zu speichern. Weitere Informationen zu möglichen Kombinationen von Lade- und Speicherformaten, die von GroupDocs.Assembly unterstützt werden, finden Sie in der Online-Dokumentation von GroupDocs.Assembly.

### Siehe auch

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
