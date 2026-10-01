---
title: "XmlDataSource"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona acceso a los datos de un archivo XML o flujo para ser utilizados al ensamblar un documento."
type: docs
weight: 260
url: /es/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

Proporciona acceso a los datos de un archivo XML o flujo para ser utilizados al ensamblar un documento.

```csharp
public class XmlDataSource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | Crea una nueva fuente de datos con datos de un flujo XML utilizando las opciones predeterminadas para la carga de datos XML. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | Crea una nueva fuente de datos con datos de un archivo XML utilizando las opciones predeterminadas para la carga de datos XML. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | Crea una nueva fuente de datos con datos de un flujo XML utilizando un flujo de definición de esquema XML (XSD). Se utilizan las opciones predeterminadas para la carga de datos XML. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | Crea una nueva fuente de datos con datos de un flujo XML utilizando las opciones especificadas para la carga de datos XML. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | Crea una nueva fuente de datos con datos de un archivo XML utilizando un archivo de Definición de Esquema XML. Se utilizan opciones predeterminadas para la carga de datos XML. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | Crea una nueva fuente de datos con datos de un archivo XML utilizando las opciones especificadas para la carga de datos XML. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | Crea una nueva fuente de datos con datos de un flujo XML utilizando un flujo de Definición de Esquema XML. Se utilizan las opciones especificadas para la carga de datos XML. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | Crea una nueva fuente de datos con datos de un archivo XML utilizando un archivo de Definición de Esquema XML. Se utilizan las opciones especificadas para la carga de datos XML. |

### Observaciones

Para acceder a los datos del archivo o flujo correspondiente al ensamblar un documento, pase una instancia de esta clase como fuente de datos a una de las sobrecargas de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

En los documentos de plantilla, si un elemento XML de nivel superior contiene solo una lista de elementos del mismo tipo, una instancia de [`XmlDataSource`](../xmldatasource) debe tratarse de la misma manera que si fuera una instancia de DataTable. De lo contrario, una instancia de [`XmlDataSource`](../xmldatasource) debe tratarse de la misma manera que si fuera una instancia de DataRow. Para obtener más información, consulte la referencia de sintaxis de plantillas (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Cuando se pasa una Definición de Esquema XML al constructor de esta clase, los tipos de datos de los valores de los elementos y atributos XML simples se determinan de acuerdo con el esquema. Por lo tanto, en los documentos de plantilla, puede trabajar con valores tipados en lugar de solo cadenas.

Cuando no se pasa una Definición de Esquema XML al constructor de esta clase, los tipos de datos de los valores de los elementos y atributos XML simples se determinan automáticamente a partir de sus representaciones en cadena. Por lo tanto, en los documentos de plantilla, también puede trabajar con valores tipados en este caso. El motor es capaz de reconocer automáticamente valores de los siguientes tipos:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Tenga en cuenta que, para que funcione el reconocimiento automático de tipos de datos, las representaciones en cadena de los valores de los elementos y atributos XML simples deben formarse utilizando configuraciones de cultura invariable.

Para sobrescribir el comportamiento predeterminado de la carga de datos XML, inicialice y pase una instancia de [`XmlDataLoadOptions`](../xmldataloadoptions) al constructor de esta clase.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
