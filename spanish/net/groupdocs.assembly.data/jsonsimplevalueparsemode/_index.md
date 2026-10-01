---
title: "JsonSimpleValueParseMode"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Especifica un modo para analizar valores simples JSON nulo, booleano, número, entero y cadena al cargar JSON. Este modo no afecta el análisis de valores de fecha y hora."
type: docs
weight: 240
url: /es/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

Especifica un modo para analizar valores simples JSON (null, booleano, número, entero y cadena) al cargar JSON. Este modo no afecta el análisis de valores de fecha y hora.

```csharp
public enum JsonSimpleValueParseMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Loose | `0` | Especifica el modo en el que los tipos de valores simples JSON se determinan al analizar sus representaciones en cadena. Por ejemplo, el tipo de 'prop' del fragmento JSON '{ prop: \"123\" }' se determina como entero en este modo. |
| Strict | `1` | Especifica el modo en el que los tipos de valores simples JSON se determinan a partir de la notación JSON misma. Por ejemplo, el tipo de 'prop' del fragmento JSON '{ prop: \"123\" }' se determina como cadena en este modo. |

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
