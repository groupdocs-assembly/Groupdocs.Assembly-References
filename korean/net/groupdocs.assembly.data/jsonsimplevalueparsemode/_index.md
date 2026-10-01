---
title: "JsonSimpleValueParseMode"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "JSON을 로드하는 동안 JSON 단순 값(null, boolean, number, integer, string)을 구문 분석하기 위한 모드를 지정합니다. 이 모드는 datetime 값의 구문 분석에는 영향을 주지 않습니다."
type: docs
weight: 240
url: /ko/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

JSON을 로드하는 동안 JSON 단순 값(null, boolean, number, integer, string)을 구문 분석하기 위한 모드를 지정합니다. 이러한 모드는 날짜-시간 값의 구문 분석에 영향을 주지 않습니다.

```csharp
public enum JsonSimpleValueParseMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Loose | `0` | JSON 단순 값의 유형을 문자열 표현을 구문 분석하면서 결정하는 모드를 지정합니다. 예를 들어, JSON 스니펫 '{ prop: \"123\" }'에서 'prop'의 유형은 이 모드에서 정수(integer)로 결정됩니다. |
| Strict | `1` | JSON 단순 값의 유형을 JSON 표기 자체에서 결정하는 모드를 지정합니다. 예를 들어, JSON 스니펫 '{ prop: \"123\" }'에서 'prop'의 유형은 이 모드에서 문자열(string)로 결정됩니다. |

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
