---
title: "DocumentTable"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 사용할 외부 문서에 위치한 단일 테이블 또는 스프레드시트의 데이터에 대한 액세스를 제공합니다."
type: docs
weight: 120
url: /ko/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

문서를 조립하는 동안 사용할 외부 문서에 위치한 단일 테이블(또는 스프레드시트)의 데이터에 대한 액세스를 제공합니다.

```csharp
public class DocumentTable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | 기본 [`DocumentTableOptions`](../documenttableoptions)을 사용하여 이 클래스의 새 인스턴스를 생성합니다. |
| [DocumentTable](documenttable#constructor_2)(string, int) | 기본 [`DocumentTableOptions`](../documenttableoptions)을 사용하여 이 클래스의 새 인스턴스를 생성합니다. |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | 이 클래스의 새 인스턴스를 생성합니다. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | 이 클래스의 새 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | 해당 테이블의 열을 나타내는 [`DocumentTableColumn`](../documenttablecolumn) 객체 컬렉션을 가져옵니다. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | 소스 문서에 따라 해당 테이블의 원래 0 기반 인덱스를 가져옵니다. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | 템플릿 문서에서 테이블 데이터를 액세스하기 위해 [`DocumentAssembler`](../../groupdocs.assembly/documentassembler)에 전달된 이 테이블의 이름을 가져오거나 설정합니다. |

### 비고

스프레드시트 파일 형식의 문서에서는 [`DocumentTable`](../documenttable) 인스턴스가 단일 시트를 나타냅니다. 다른 파일 형식의 문서에서는 [`DocumentTable`](../documenttable) 인스턴스가 단일 테이블을 나타냅니다.

문서를 조립하는 동안 해당 테이블의 데이터에 액세스하려면 이 클래스의 인스턴스를 데이터 소스로 전달하여 [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 오버로드 중 하나에 사용하십시오.

템플릿 문서에서는 [`DocumentTable`](../documenttable) 인스턴스를 DataTable 인스턴스처럼 취급해야 합니다. 자세한 내용은 템플릿 구문 참조를 확인하십시오.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
