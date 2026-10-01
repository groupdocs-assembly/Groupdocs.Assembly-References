---
title: "DocumentTableCollection"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "특정 DocumentTableSet./documenttableset 인스턴스의 DocumentTable./documenttable 객체들로 구성된 읽기 전용 컬렉션을 나타냅니다."
type: docs
weight: 130
url: /ko/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

특정 [`DocumentTableSet`](../documenttableset) 인스턴스의 [`DocumentTable`](../documenttable) 객체들로 구성된 읽기 전용 컬렉션을 나타냅니다.

```csharp
public class DocumentTableCollection : IEnumerable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | 컬렉션에 포함된 [`DocumentTable`](../documenttable) 객체의 총 개수를 가져옵니다. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | 지정된 인덱스에서 컬렉션의 [`DocumentTable`](../documenttable) 인스턴스를 가져옵니다. (2개의 인덱서) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | 이 컬렉션에 지정된 테이블이 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | 이 컬렉션에 지정된 이름을 가진 테이블이 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | 이 컬렉션의 [`DocumentTable`](../documenttable) 객체들을 반복하는 열거자를 반환합니다. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | 이 컬렉션 내에서 지정된 테이블의 인덱스를 반환합니다. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | 이 컬렉션 내에서 지정된 이름을 가진 테이블의 인덱스를 반환합니다. |

### 비고

컬렉션은 문서에서 해당 테이블을 로드하는 동안 자동으로 채워지며 수정할 수 없습니다. 그러나 컬렉션에 포함된 [`DocumentTable`](../documenttable) 객체의 속성은 수정할 수 있습니다.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
