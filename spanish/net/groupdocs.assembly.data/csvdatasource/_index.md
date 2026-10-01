---
title: "CsvDataSource"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona acceso a los datos de un archivo CSV o flujo para ser utilizados al ensamblar un documento."
type: docs
weight: 110
url: /es/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

Proporciona acceso a los datos de un archivo CSV o flujo para ser utilizados al ensamblar un documento.

```csharp
public class CsvDataSource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | Crea una nueva fuente de datos con datos de un flujo CSV utilizando las opciones predeterminadas para analizar datos CSV. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | Crea una nueva fuente de datos con datos de un archivo CSV utilizando las opciones predeterminadas para analizar datos CSV. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | Crea una nueva fuente de datos con datos de un flujo CSV utilizando las opciones especificadas para analizar datos CSV. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | Crea una nueva fuente de datos con datos de un archivo CSV utilizando las opciones especificadas para analizar datos CSV. |

### Observaciones

Para acceder a los datos del archivo o flujo correspondiente al ensamblar un documento, pase una instancia de esta clase como fuente de datos a una de las sobrecargas de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

En los documentos de plantilla, una instancia de [`CsvDataSource`](../csvdatasource) debe tratarse de la misma manera que si fuera una instancia de DataTable. Para obtener más información, consulte la referencia de sintaxis de plantillas (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Los tipos de datos de los valores separados por comas se determinan automáticamente a partir de sus representaciones en cadena. Por lo tanto, en los documentos de plantilla, puede trabajar con valores tipados en lugar de solo cadenas. El motor es capaz de reconocer automáticamente valores de los siguientes tipos:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Tenga en cuenta que, para que funcione el reconocimiento automático de tipos de datos, las representaciones en cadena de los valores separados por comas deben formarse utilizando configuraciones de cultura invariable.

Para sobrescribir el comportamiento predeterminado de la carga de datos CSV, inicialice y pase una instancia de [`CsvDataLoadOptions`](../csvdataloadoptions) al constructor de esta clase.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
