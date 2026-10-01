---
title: "DataSource"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "데이터 소스 개체를 가져오거나 설정합니다."
type: docs
weight: 20
url: /ko/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

데이터 소스 개체를 가져오거나 설정합니다.

```csharp
public object DataSource { get; set; }
```

### 비고

데이터 소스 객체는 다음 유형 중 하나일 수 있습니다:

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

템플릿 문서에서 다양한 유형의 데이터 소스를 사용하는 방법에 대한 정보는 템플릿 구문 참조(https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)를 참조하십시오.

### 관련 항목

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
