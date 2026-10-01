---
title: "JsonDataLoadOptions"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Representa opciones para analizar datos JSON."
type: docs
weight: 220
url: /es/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

Representa opciones para analizar datos JSON.

```csharp
public class JsonDataLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | Inicializa una nueva instancia de esta clase con opciones predeterminadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | Obtiene o establece una bandera que indica si una fuente de datos generada siempre contendrá un objeto para un elemento raíz JSON. Si un elemento raíz JSON contiene una única propiedad compleja, dicho objeto no se crea de forma predeterminada. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | Obtiene o establece formatos exactos para analizar valores de fecha y hora JSON al cargar JSON. El valor predeterminado es **null**. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | Obtiene o establece un modo para analizar valores simples JSON (null, booleano, número, entero y cadena) al cargar JSON. Ese modo no afecta el análisis de valores de fecha y hora. El valor predeterminado es Loose. |

### Observaciones

Una instancia de esta clase puede pasarse a los constructores de [`JsonDataSource`](../jsondatasource).

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
