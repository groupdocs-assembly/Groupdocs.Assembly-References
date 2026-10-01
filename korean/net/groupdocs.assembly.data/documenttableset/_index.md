---
title: "DocumentTableSet"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 사용할 외부 문서에 위치한 여러 테이블 또는 스프레드시트의 데이터에 대한 액세스를 제공합니다. 또한 문서 테이블에 대한 부모-자식 관계를 정의할 수 있게 하여 템플릿 문서 내에서 관련 데이터에 대한 액세스를 단순화합니다."
type: docs
weight: 200
url: /ko/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

문서를 조립하는 동안 사용할 외부 문서에 위치한 여러 테이블(또는 스프레드시트)의 데이터에 대한 액세스를 제공합니다. 또한 문서 테이블에 대한 부모-자식 관계를 정의할 수 있게 하여 템플릿 문서 내에서 관련 데이터에 대한 접근을 단순화합니다.

```csharp
public class DocumentTableSet
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | 이 클래스의 새 인스턴스를 생성하여 문서에서 모든 테이블을 기본 [`DocumentTableOptions`](../documenttableoptions)으로 로드합니다. |
| [DocumentTableSet](documenttableset#constructor_2)(string) | 이 클래스의 새 인스턴스를 생성하여 문서에서 모든 테이블을 기본 [`DocumentTableOptions`](../documenttableoptions)으로 로드합니다. |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | 이 클래스의 새 인스턴스를 생성합니다. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | 이 클래스의 새 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | 이 세트의 문서 테이블에 대해 정의된 부모-자식 관계 컬렉션을 가져옵니다. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | 이 세트의 테이블을 나타내는 [`DocumentTable`](../documenttable) 객체 컬렉션을 가져옵니다. |

### 비고

스프레드시트 파일 형식의 문서에 대해, [`DocumentTableSet`](../documenttableset) 인스턴스는 시트 집합을 나타냅니다. 다른 파일 형식의 문서에 대해, [`DocumentTableSet`](../documenttableset) 인스턴스는 테이블 집합을 나타냅니다.

문서를 조립하는 동안 해당 테이블의 데이터에 액세스하려면, 이 클래스의 인스턴스를 데이터 소스로 전달하여 [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 오버로드 중 하나에 사용하십시오.

템플릿 문서에서, [`DocumentTableSet`](../documenttableset) 인스턴스는 DataSet 인스턴스인 것처럼 동일하게 취급해야 합니다. 자세한 내용은 템플릿 구문 참조를 확인하십시오.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
