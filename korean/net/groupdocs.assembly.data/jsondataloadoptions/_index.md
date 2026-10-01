---
title: "JsonDataLoadOptions"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "JSON 데이터 구문 분석 옵션을 나타냅니다."
type: docs
weight: 220
url: /ko/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

JSON 데이터 구문 분석 옵션을 나타냅니다.

```csharp
public class JsonDataLoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | 기본 옵션으로 이 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | 생성된 데이터 소스가 JSON 루트 요소에 대해 항상 객체를 포함할지 여부를 나타내는 플래그를 가져오거나 설정합니다. JSON 루트 요소에 단일 복합 속성이 포함된 경우 기본적으로 해당 객체는 생성되지 않습니다. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | JSON을 로드하는 동안 JSON 날짜‑시간 값을 구문 분석하기 위한 정확한 형식을 가져오거나 설정합니다. 기본값은 **null**입니다. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | JSON을 로드하는 동안 JSON 단순 값(null, boolean, number, integer, string)을 구문 분석하기 위한 모드를 가져오거나 설정합니다. 이 모드는 날짜‑시간 값 구문 분석에 영향을 주지 않습니다. 기본값은 Loose입니다. |

### 비고

이 클래스의 인스턴스를 [`JsonDataSource`](../jsondatasource) 생성자에 전달할 수 있습니다.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
