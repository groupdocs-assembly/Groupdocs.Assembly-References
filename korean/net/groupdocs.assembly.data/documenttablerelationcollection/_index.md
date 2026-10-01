---
title: "DocumentTableRelationCollection"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "단일 DocumentTableSet./documenttableset 인스턴스의 DocumentTableRelation./documenttablerelation 객체 컬렉션을 나타냅니다."
type: docs
weight: 190
url: /ko/net/groupdocs.assembly.data/documenttablerelationcollection/
---
## DocumentTableRelationCollection class

단일 [`DocumentTableSet`](../documenttableset) 인스턴스의 [`DocumentTableRelation`](../documenttablerelation) 객체 컬렉션을 나타냅니다.

```csharp
public class DocumentTableRelationCollection : IEnumerable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablerelationcollection/count) { get; } | 컬렉션에 포함된 [`DocumentTableRelation`](../documenttablerelation) 객체의 총 개수를 가져옵니다. |
| [Item](../../groupdocs.assembly.data/documenttablerelationcollection/item) { get; } | 지정된 인덱스에서 컬렉션의 [`DocumentTableRelation`](../documenttablerelation) 인스턴스를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../groupdocs.assembly.data/documenttablerelationcollection/add)(DocumentTableColumn, DocumentTableColumn) | 지정된 부모 및 자식 열에 대한 [`DocumentTableRelation`](../documenttablerelation) 객체를 생성하고 컬렉션에 추가합니다. |
| [Clear](../../groupdocs.assembly.data/documenttablerelationcollection/clear)() | 컬렉션의 모든 관계를 제거합니다. |
| [Contains](../../groupdocs.assembly.data/documenttablerelationcollection/contains)(DocumentTableRelation) | 이 컬렉션에 지정된 관계가 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablerelationcollection/getenumerator)() | 이 컬렉션의 [`DocumentTableRelation`](../documenttablerelation) 객체를 반복하기 위한 열거자를 반환합니다. |
| [IndexOf](../../groupdocs.assembly.data/documenttablerelationcollection/indexof)(DocumentTableRelation) | 이 컬렉션 내에서 지정된 관계의 인덱스를 반환합니다. |
| [Remove](../../groupdocs.assembly.data/documenttablerelationcollection/remove)(DocumentTableRelation) | 컬렉션에서 지정된 관계를 제거합니다. |
| [RemoveAt](../../groupdocs.assembly.data/documenttablerelationcollection/removeat)(int) | 컬렉션에서 지정된 인덱스에 있는 관계를 제거합니다. |

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
