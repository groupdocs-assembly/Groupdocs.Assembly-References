---
title: DataSourceInfo
second_title: GroupDocs.Assembly for .NET API 参考
description: 创建此类的新实例但未指定任何属性
type: docs
weight: 10
url: /zh/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

创建此类的新实例，但未指定任何属性。

```csharp
public DataSourceInfo()
```

### 也可以看看

* class [DataSourceInfo](../../datasourceinfo)
* 命名空间 [GroupDocs.Assembly](../../datasourceinfo)
* 部件 [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

使用指定的数据源对象创建此类的新实例。

```csharp
public DataSourceInfo(object dataSource)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| dataSource | Object | 数据源对象。 |

### 评论

数据源对象可以是以下类型之一：

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
* 任何其他任意非动态和非匿名 .NET 类型

有关如何在模板文档中使用不同类型的数据源的信息，请参阅模板语法参考 (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2# TemplateSyntax-Part1of2-UsingDataSources).

### 也可以看看

* class [DataSourceInfo](../../datasourceinfo)
* 命名空间 [GroupDocs.Assembly](../../datasourceinfo)
* 部件 [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

使用指定的数据源对象及其名称创建此类的新实例。

```csharp
public DataSourceInfo(object dataSource, string name)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| dataSource | Object | 数据源对象。 |
| name | String | 用于访问模板文档中的数据源对象的数据源对象的名称。 |

### 评论

数据源对象可以是以下类型之一：

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
* 任何其他任意非动态和非匿名 .NET 类型

有关如何在模板文档中使用不同类型的数据源的信息，请参阅模板语法参考 (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2# TemplateSyntax-Part1of2-UsingDataSources).

指定数据源对象的名称后，您可以在模板文档中使用该名称访问数据源对象及其成员 。

当数据源对象的名称为 null 或为空时，您仍然可以使用上下文对象成员访问在模板文档中访问数据源对象 的成员（更多信息请参阅模板语法参考）， 但您无法访问数据源对象本身。

传递多个时[`DataSourceInfo`](../../datasourceinfo)实例到[`DocumentAssembler`](../../documentassembler)，只有 第一个数据源对象的名称可以为null或为空。其余名称必须指定且唯一。

### 也可以看看

* class [DataSourceInfo](../../datasourceinfo)
* 命名空间 [GroupDocs.Assembly](../../datasourceinfo)
* 部件 [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->