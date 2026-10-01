---
title: "SaveFormat"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece un formato de archivo para guardar un documento ensamblado. No especificado es el valor predeterminado."
type: docs
weight: 40
url: /es/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

Obtiene o establece un formato de archivo para guardar un documento ensamblado. No especificado es el valor predeterminado.

```csharp
public FileFormat SaveFormat { get; set; }
```

### Observaciones

Cuando el valor de esta propiedad no se especifica, [`DocumentAssembler`](../../documentassembler) se comporta de la siguiente manera:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

Tenga en cuenta que no siempre es posible guardar un documento ensamblado en cualquier formato de archivo usando GroupDocs.Assembly. Por ejemplo, es imposible guardar un documento cargado desde un formato de procesamiento de texto (como DOCX) en un formato de hoja de cálculo (como XLSX). Para obtener más información sobre las combinaciones posibles de formatos de archivo de carga y guardado compatibles con GroupDocs.Assembly, consulte la documentación en línea de GroupDocs.Assembly.

### Ver también

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
