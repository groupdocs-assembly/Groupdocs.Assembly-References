---
title: "IndexOf"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "이 컬렉션 내에서 지정된 이름을 가진 열의 인덱스를 반환합니다."
type: docs
weight: 50
url: /ko/net/groupdocs.assembly.data/documenttablecolumncollection/indexof/
---
## IndexOf(string) {#indexof_1}

이 컬렉션 내에서 지정된 이름을 가진 열의 인덱스를 반환합니다.

```csharp
public int IndexOf(string name)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | String | 찾을 열의 대소문자를 구분하지 않는 이름입니다. |

### 반환 값

지정된 이름을 가진 열의 0부터 시작하는 인덱스이며, 컬렉션에 열이 존재하지 않으면 -1을 반환합니다.

### 관련 항목

* class [DocumentTableColumnCollection](../../documenttablecolumncollection)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumncollection)
* assembly [GroupDocs.Assembly](../../../)

---

## IndexOf(DocumentTableColumn) {#indexof}

이 컬렉션 내에서 지정된 열의 인덱스를 반환합니다.

```csharp
public int IndexOf(DocumentTableColumn column)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 열 | DocumentTableColumn | 찾을 열입니다. |

### 반환 값

지정된 열의 0부터 시작하는 인덱스이며, 컬렉션에 열이 존재하지 않으면 -1을 반환합니다.

### 관련 항목

* class [DocumentTableColumn](../../documenttablecolumn)
* class [DocumentTableColumnCollection](../../documenttablecolumncollection)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumncollection)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
