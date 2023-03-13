---
title: DataSource
second_title: GroupDocs.Assembly for .NET API リファレンス
description: データ ソース オブジェクトを取得または設定します
type: docs
weight: 20
url: /ja/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

データ ソース オブジェクトを取得または設定します。

```csharp
public object DataSource { get; set; }
```

### 備考

データ ソース オブジェクトは、次のいずれかのタイプにすることができます:

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
* その他の任意の非動的かつ非匿名の .NET type

テンプレート ドキュメントでさまざまな種類のデータ ソースを操作する方法については、テンプレート構文リファレンス (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2# TemplateSyntax-Part1of2-UsingDataSources).

### 関連項目

* class [DataSourceInfo](../../datasourceinfo)
* 名前空間 [GroupDocs.Assembly](../../datasourceinfo)
* 組み立て [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->