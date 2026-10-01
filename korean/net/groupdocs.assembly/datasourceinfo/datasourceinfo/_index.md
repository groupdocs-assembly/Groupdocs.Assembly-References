---
title: "DataSourceInfo"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "이 클래스의 새 인스턴스를 속성을 지정하지 않고 생성합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

이 클래스의 새 인스턴스를 속성을 지정하지 않고 생성합니다.

```csharp
public DataSourceInfo()
```

### 관련 항목

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

지정된 데이터 소스 개체를 사용하여 이 클래스의 새 인스턴스를 생성합니다.

```csharp
public DataSourceInfo(object dataSource)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataSource | Object | 데이터 소스 객체. |

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

---

## DataSourceInfo(object, string) {#constructor_2}

데이터 소스 개체와 해당 이름을 지정하여 이 클래스의 새 인스턴스를 생성합니다.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataSource | Object | 데이터 소스 객체. |
| name | String | 템플릿 문서에서 데이터 소스 객체에 접근하기 위해 사용할 데이터 소스 객체의 이름. |

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

데이터 소스 객체의 이름이 지정된 경우, 해당 이름을 사용하여 템플릿 문서에서 데이터 소스 객체와 그 멤버에 접근할 수 있습니다.

데이터 소스 객체의 이름이 null이거나 비어 있는 경우에도 컨텍스트 객체 멤버 접근(자세한 내용은 Template Syntax Reference를 참조)을 사용하여 템플릿 문서에서 데이터 소스 객체의 멤버에 접근할 수 있지만, 데이터 소스 객체 자체에는 접근할 수 없습니다.

여러 개의 [`DataSourceInfo`](../../datasourceinfo) 인스턴스를 [`DocumentAssembler`](../../documentassembler)에 전달할 때, 첫 번째 데이터 소스 객체의 이름만 null이거나 비어 있을 수 있습니다. 나머지 객체들의 이름은 지정되어야 하며 고유해야 합니다.

### 관련 항목

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
