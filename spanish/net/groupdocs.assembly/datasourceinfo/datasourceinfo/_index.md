---
title: "DataSourceInfo"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Crea una nueva instancia de esta clase sin especificar ninguna propiedad."
type: docs
weight: 10
url: /es/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

Crea una nueva instancia de esta clase sin especificar ninguna propiedad.

```csharp
public DataSourceInfo()
```

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

Crea una nueva instancia de esta clase con el objeto de origen de datos especificado.

```csharp
public DataSourceInfo(object dataSource)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| dataSource | Object | El objeto de origen de datos. |

### Observaciones

El objeto de origen de datos puede ser de uno de los siguientes tipos:

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

Para obtener información sobre cómo trabajar con orígenes de datos de diferentes tipos en documentos de plantilla, consulte la referencia de sintaxis de plantilla (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

Crea una nueva instancia de esta clase con el objeto de origen de datos y su nombre especificados.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| dataSource | Object | El objeto de origen de datos. |
| name | String | El nombre del objeto de origen de datos que se utilizará para acceder al objeto de origen de datos en un documento de plantilla. |

### Observaciones

El objeto de origen de datos puede ser de uno de los siguientes tipos:

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

Para obtener información sobre cómo trabajar con orígenes de datos de diferentes tipos en documentos de plantilla, consulte la referencia de sintaxis de plantilla (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Cuando se especifica el nombre del objeto de origen de datos, puede acceder al objeto de origen de datos y a sus miembros en un documento de plantilla usando el nombre.

Cuando el nombre del objeto de origen de datos es nulo o vacío, aún puede acceder a los miembros del objeto de origen de datos en un documento de plantilla usando el acceso a miembros del objeto de contexto (consulte Referencia de Sintaxis de Plantilla para más información), pero no puede acceder al propio objeto de origen de datos.

Al pasar múltiples instancias de [`DataSourceInfo`](../../datasourceinfo) a [`DocumentAssembler`](../../documentassembler), solo el nombre del primer objeto de origen de datos puede ser nulo o vacío. Los nombres del resto deben especificarse y ser únicos.

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
