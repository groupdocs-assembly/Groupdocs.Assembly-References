---
title: "ExactDateTimeParseFormats"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "JSON을 로드하는 동안 JSON datetime 값을 구문 분석하기 위한 정확한 형식을 가져오거나 설정합니다. 기본값은 null입니다."
type: docs
weight: 30
url: /ko/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

JSON을 로드하는 동안 JSON 날짜‑시간 값을 구문 분석하기 위한 정확한 형식을 가져오거나 설정합니다. 기본값은 **null**입니다.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### 비고

Microsoft® JSON 날짜-시간 형식(예: "/Date(1224043200000)/")으로 인코딩된 문자열은 이 속성의 값과 관계없이 항상 날짜-시간 값으로 인식됩니다. 이 속성은 문자열에서 날짜-시간 값을 구문 분석할 때 다음과 같이 사용할 추가 형식을 정의합니다:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### 관련 항목

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
