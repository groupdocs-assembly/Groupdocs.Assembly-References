---
title: "DataSourceInfo"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bu sınıfın hiçbir özellik belirtilmeden yeni bir örneğini oluşturur."
type: docs
weight: 10
url: /tr/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

Bu sınıfın hiçbir özellik belirtilmeden yeni bir örneğini oluşturur.

```csharp
public DataSourceInfo()
```

### Ayrıca Bakınız

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

Belirtilen veri kaynağı nesnesiyle bu sınıfın yeni bir örneğini oluşturur.

```csharp
public DataSourceInfo(object dataSource)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataSource | Object | Veri kaynağı nesnesi. |

### Açıklamalar

Veri kaynağı nesnesi aşağıdaki türlerden biri olabilir:

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

Şablon belgelerinde farklı türde veri kaynaklarıyla nasıl çalışılacağı hakkında bilgi için, şablon sözdizimi referansına bakın (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Ayrıca Bakınız

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

Veri kaynağı nesnesi ve adı belirtilerek bu sınıfın yeni bir örneğini oluşturur.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataSource | Object | Veri kaynağı nesnesi. |
| name | String | Şablon belgesinde veri kaynağı nesnesine erişmek için kullanılacak veri kaynağı nesnesinin adı. |

### Açıklamalar

Veri kaynağı nesnesi aşağıdaki türlerden biri olabilir:

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

Şablon belgelerinde farklı türde veri kaynaklarıyla nasıl çalışılacağı hakkında bilgi için, şablon sözdizimi referansına bakın (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Veri kaynağı nesnesinin adı belirtildiğinde, şablon belgesinde veri kaynağı nesnesine ve üyelerine adı kullanarak erişebilirsiniz.

Veri kaynağı nesnesinin adı null veya boş olduğunda, şablon belgesinde bağlam nesnesi üye erişimini kullanarak (daha fazla bilgi için Template Syntax Reference bölümüne bakın) yine de veri kaynağı nesnesinin üyelerine erişebilirsiniz, ancak veri kaynağı nesnesine doğrudan erişemezsiniz.

Birden fazla [`DataSourceInfo`](../../datasourceinfo) örneğini [`DocumentAssembler`](../../documentassembler)'a gönderirken, yalnızca ilk veri kaynağı nesnesinin adı null veya boş olabilir. Diğerlerinin adları belirtilmeli ve benzersiz olmalıdır.

### Ayrıca Bakınız

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
