---
title: "JsonDataSource"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona acceso a los datos de un archivo JSON o flujo para ser utilizados al ensamblar un documento."
type: docs
weight: 230
url: /es/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Proporciona acceso a los datos de un archivo JSON o flujo para ser utilizados al ensamblar un documento.

```csharp
public class JsonDataSource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | Crea una nueva fuente de datos con datos de un flujo JSON utilizando las opciones predeterminadas para analizar datos JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | Crea una nueva fuente de datos con datos de un archivo JSON utilizando las opciones predeterminadas para analizar datos JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | Crea una nueva fuente de datos con datos de un flujo JSON utilizando las opciones especificadas para analizar datos JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | Crea una nueva fuente de datos con datos de un archivo JSON utilizando las opciones especificadas para analizar datos JSON. |

### Observaciones

Para acceder a los datos del archivo o flujo correspondiente al ensamblar un documento, pase una instancia de esta clase como fuente de datos a una de las sobrecargas de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

En los documentos de plantilla, si un elemento JSON de nivel superior es una matriz, una instancia de [`JsonDataSource`](../jsondatasource) debe tratarse de la misma manera que si fuera una instancia de DataTable. Si un elemento JSON de nivel superior es un objeto, una instancia de [`JsonDataSource`](../jsondatasource) debe tratarse de la misma manera que si fuera una instancia de DataRow. Para obtener más información, consulte la referencia de sintaxis de plantillas (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

En los documentos de plantilla, puede trabajar con valores tipados de los elementos JSON. Para mayor comodidad, el motor reemplaza el conjunto de tipos simples JSON con el siguiente:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

El motor reconoce automáticamente los valores de los tipos adicionales a partir de sus representaciones JSON.

Para sobrescribir el comportamiento predeterminado de la carga de datos JSON, inicialice y pase una instancia de [`JsonDataLoadOptions`](../jsondataloadoptions) a un constructor de esta clase.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
