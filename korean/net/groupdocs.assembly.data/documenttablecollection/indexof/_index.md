---
title: "IndexOf"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "이 컬렉션 내에서 지정된 이름을 가진 테이블의 인덱스를 반환합니다."
type: docs
weight: 50
url: /ko/net/groupdocs.assembly.data/documenttablecollection/indexof/
---
## IndexOf(string) {#indexof_1}

이 컬렉션 내에서 지정된 이름을 가진 테이블의 인덱스를 반환합니다.

```csharp
public int IndexOf(string name)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | String | 찾을 테이블의 대소문자를 구분하지 않는 이름입니다. |

### 반환 값

지정된 이름을 가진 테이블의 0부터 시작하는 인덱스이며, 컬렉션에 테이블이 없으면 -1을 반환합니다.

### 관련 항목

* class [DocumentTableCollection](../../documenttablecollection)
* namespace [GroupDocs.Assembly.Data](../../documenttablecollection)
* assembly [GroupDocs.Assembly](../../../)

---

## IndexOf(DocumentTable) {#indexof}

이 컬렉션 내에서 지정된 테이블의 인덱스를 반환합니다.

```csharp
public int IndexOf(DocumentTable table)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 테이블 | DocumentTable | 찾을 테이블입니다. |

### 반환 값

지정된 테이블의 0부터 시작하는 인덱스이며, 컬렉션에 테이블이 없으면 -1을 반환합니다.

### 관련 항목

* class [DocumentTable](../../documenttable)
* class [DocumentTableCollection](../../documenttablecollection)
* namespace [GroupDocs.Assembly.Data](../../documenttablecollection)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
