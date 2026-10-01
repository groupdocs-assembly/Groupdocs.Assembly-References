---
title: "DocumentTableColumnCollection"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "특정 DocumentTable./documenttable 인스턴스의 DocumentTableColumn./documenttablecolumn 객체들로 구성된 읽기 전용 컬렉션을 나타냅니다."
type: docs
weight: 150
url: /ko/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

특정 [`DocumentTable`](../documenttable) 인스턴스의 [`DocumentTableColumn`](../documenttablecolumn) 객체들로 구성된 읽기 전용 컬렉션을 나타냅니다.

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | 컬렉션에 포함된 [`DocumentTableColumn`](../documenttablecolumn) 객체의 총 개수를 가져옵니다. |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | 지정된 인덱스에서 컬렉션의 [`DocumentTableColumn`](../documenttablecolumn) 인스턴스를 가져옵니다. (2개의 인덱서) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | 이 컬렉션에 지정된 열이 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | 이 컬렉션에 지정된 이름을 가진 열이 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | 이 컬렉션의 [`DocumentTableColumn`](../documenttablecolumn) 객체들을 반복할 수 있는 열거자를 반환합니다. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | 이 컬렉션 내에서 지정된 열의 인덱스를 반환합니다. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | 이 컬렉션 내에서 지정된 이름을 가진 열의 인덱스를 반환합니다. |

### 비고

컬렉션은 문서에서 해당 테이블을 로드하는 동안 자동으로 채워지며 수정할 수 없습니다. 그러나 컬렉션에 포함된 [`DocumentTableColumn`](../documenttablecolumn) 객체의 속성은 수정할 수 있습니다.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
