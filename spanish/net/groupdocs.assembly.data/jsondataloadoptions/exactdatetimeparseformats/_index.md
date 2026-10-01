---
title: "ExactDateTimeParseFormats"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece formatos exactos para analizar valores de fecha y hora JSON al cargar JSON. El valor predeterminado es null."
type: docs
weight: 30
url: /es/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

Obtiene o establece formatos exactos para analizar valores de fecha y hora JSON al cargar JSON. El valor predeterminado es **null**.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Observaciones

Las cadenas codificadas usando el formato de fecha y hora JSON de Microsoft® (por ejemplo, "\/Date(1224043200000)\/" ) siempre se reconocen como valores de fecha y hora sin importar el valor de esta propiedad. La propiedad define formatos adicionales que se usarán al analizar valores de fecha y hora a partir de cadenas de la siguiente manera:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### Ver también

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
