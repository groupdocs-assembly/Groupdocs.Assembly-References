---
title: "CsvDataLoadOptions"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "CSV 데이터를 구문 분석하기 위한 옵션을 나타냅니다."
type: docs
weight: 100
url: /ko/net/groupdocs.assembly.data/csvdataloadoptions/
---
## CsvDataLoadOptions class

CSV 데이터를 구문 분석하기 위한 옵션을 나타냅니다.

```csharp
public class CsvDataLoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CsvDataLoadOptions](csvdataloadoptions#constructor)() | 기본 옵션으로 이 클래스의 새 인스턴스를 초기화합니다. |
| [CsvDataLoadOptions](csvdataloadoptions#constructor_1)(bool) | CSV 데이터가 첫 번째 줄에 열 이름을 포함하는지 여부를 지정하여 이 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CommentChar](../../groupdocs.assembly.data/csvdataloadoptions/commentchar) { get; set; } | CSV 데이터의 행에 주석을 달 때 사용되는 문자를 가져오거나 설정합니다. |
| [Delimiter](../../groupdocs.assembly.data/csvdataloadoptions/delimiter) { get; set; } | 열 구분 기호로 사용할 문자를 가져오거나 설정합니다. |
| [HasHeaders](../../groupdocs.assembly.data/csvdataloadoptions/hasheaders) { get; set; } | CSV 데이터의 첫 번째 줄에 열 이름이 포함되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [QuoteChar](../../groupdocs.assembly.data/csvdataloadoptions/quotechar) { get; set; } | 필드 값을 인용할 때 사용되는 문자를 가져오거나 설정합니다. |

### 비고

이 클래스의 인스턴스를 [`CsvDataSource`](../csvdatasource) 생성자에 전달할 수 있습니다.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
