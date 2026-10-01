---
title: "추가"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "지정된 Type 객체를 집합에 추가합니다."
type: docs
weight: 20
url: /ko/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

지정된 Type 객체를 집합에 추가합니다.

다음 경우에 ArgumentException을 발생시킵니다:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 형식 | 형식 | 추가할 Type 객체입니다. |

### 관련 항목

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
