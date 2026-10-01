---
title: "GroupDocs.Assembly.Data"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 사용할 외부 문서의 데이터를 액세스하기 위한 클래스를 제공합니다."
type: docs
weight: 20
url: /ko/net/groupdocs.assembly.data/
---
문서를 조립하는 동안 사용할 외부 문서의 데이터를 액세스하기 위한 클래스를 제공합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | CSV 데이터를 구문 분석하기 위한 옵션을 나타냅니다. |
| [CsvDataSource](./csvdatasource) | 문서를 조립하는 동안 사용할 CSV 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다. |
| [DocumentTable](./documenttable) | 문서를 조립하는 동안 사용할 외부 문서에 위치한 단일 테이블(또는 스프레드시트)의 데이터에 대한 액세스를 제공합니다. |
| [DocumentTableCollection](./documenttablecollection) | 특정 [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) 인스턴스의 [`DocumentTable`](../groupdocs.assembly.data/documenttable) 객체에 대한 읽기 전용 컬렉션을 나타냅니다. |
| [DocumentTableColumn](./documenttablecolumn) | 특정 [`DocumentTable`](../groupdocs.assembly.data/documenttable) 객체의 단일 열을 나타냅니다. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | 특정 [`DocumentTable`](../groupdocs.assembly.data/documenttable) 인스턴스의 [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) 객체에 대한 읽기 전용 컬렉션을 나타냅니다. |
| [DocumentTableLoadArgs](./documenttableloadargs) | `[`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle)` 메서드에 대한 데이터를 제공합니다. |
| [DocumentTableOptions](./documenttableoptions) | 문서 테이블에서 데이터 추출을 제어하기 위한 옵션 집합을 제공합니다. |
| [DocumentTableRelation](./documenttablerelation) | 두 [`DocumentTable`](../groupdocs.assembly.data/documenttable) 객체 간의 부모-자식 관계를 나타냅니다. |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | 단일 [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) 인스턴스의 [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) 객체 컬렉션을 나타냅니다. |
| [DocumentTableSet](./documenttableset) | 문서를 조립하는 동안 사용할 외부 문서에 위치한 여러 테이블(또는 스프레드시트)의 데이터에 대한 액세스를 제공합니다. 또한 문서 테이블에 대한 부모-자식 관계를 정의할 수 있게 하여 템플릿 문서 내에서 관련 데이터에 대한 접근을 단순화합니다. |
| [JsonDataLoadOptions](./jsondataloadoptions) | JSON 데이터 구문 분석 옵션을 나타냅니다. |
| [JsonDataSource](./jsondatasource) | 문서를 조립하는 동안 사용할 JSON 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다. |
| [XmlDataLoadOptions](./xmldataloadoptions) | XML 데이터 로딩 옵션을 나타냅니다. |
| [XmlDataSource](./xmldatasource) | 문서를 조립하는 동안 사용할 XML 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | `[`DocumentTable`](../groupdocs.assembly.data/documenttable)` 객체의 기본 로드를 [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) 인스턴스를 생성하는 동안 재정의합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | JSON을 로드하는 동안 JSON 단순 값(null, boolean, number, integer, string)을 구문 분석하기 위한 모드를 지정합니다. 이러한 모드는 날짜-시간 값의 구문 분석에 영향을 주지 않습니다. |

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
