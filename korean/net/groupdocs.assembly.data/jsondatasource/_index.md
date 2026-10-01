---
title: "JsonDataSource"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 사용할 JSON 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다."
type: docs
weight: 230
url: /ko/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

문서를 조립하는 동안 사용할 JSON 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다.

```csharp
public class JsonDataSource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | JSON 데이터를 구문 분석하기 위한 기본 옵션을 사용하여 JSON 스트림의 데이터를 포함하는 새 데이터 소스를 생성합니다. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | JSON 데이터를 구문 분석하기 위한 기본 옵션을 사용하여 JSON 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | JSON 데이터를 구문 분석하기 위한 지정된 옵션을 사용하여 JSON 스트림의 데이터를 포함하는 새 데이터 소스를 생성합니다. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | JSON 데이터를 구문 분석하기 위한 지정된 옵션을 사용하여 JSON 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다. |

### 비고

문서를 조립하는 동안 해당 파일 또는 스트림의 데이터에 접근하려면, 이 클래스의 인스턴스를 데이터 소스로 전달하여 [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 오버로드 중 하나에 사용합니다.

템플릿 문서에서 최상위 JSON 요소가 배열인 경우, [`JsonDataSource`](../jsondatasource) 인스턴스는 DataTable 인스턴스로 취급하는 것과 동일하게 처리해야 합니다. 최상위 JSON 요소가 객체인 경우, [`JsonDataSource`](../jsondatasource) 인스턴스는 DataRow 인스턴스로 취급하는 것과 동일하게 처리해야 합니다. 자세한 내용은 템플릿 구문 참조(https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)를 참조하십시오.

템플릿 문서에서는 JSON 요소의 형식화된 값을 사용할 수 있습니다. 편의를 위해 엔진은 JSON 기본 유형 집합을 다음과 같이 교체합니다:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

엔진은 JSON 표현을 기반으로 추가 유형의 값을 자동으로 인식합니다.

JSON 데이터 로딩의 기본 동작을 재정의하려면, [`JsonDataLoadOptions`](../jsondataloadoptions) 인스턴스를 초기화하여 이 클래스의 생성자에 전달합니다.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
