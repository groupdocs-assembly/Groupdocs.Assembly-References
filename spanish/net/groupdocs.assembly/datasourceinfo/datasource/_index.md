---
title: "DataSource"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece el objeto de origen de datos."
type: docs
weight: 20
url: /es/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

Obtiene o establece el objeto de origen de datos.

```csharp
public object DataSource { get; set; }
```

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

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
