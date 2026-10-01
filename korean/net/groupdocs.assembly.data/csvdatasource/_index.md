---
title: "CsvDataSource"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 사용할 CSV 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다."
type: docs
weight: 110
url: /ko/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

문서를 조립하는 동안 사용할 CSV 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다.

```csharp
public class CsvDataSource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | CSV 스트림의 데이터를 사용하고 CSV 데이터를 구문 분석하기 위한 기본 옵션으로 새 데이터 소스를 생성합니다. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | CSV 파일의 데이터를 사용하고 CSV 데이터를 구문 분석하기 위한 기본 옵션으로 새 데이터 소스를 생성합니다. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | CSV 스트림의 데이터를 사용하고 CSV 데이터를 구문 분석하기 위한 지정된 옵션으로 새 데이터 소스를 생성합니다. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | CSV 파일의 데이터를 사용하고 CSV 데이터를 구문 분석하기 위한 지정된 옵션으로 새 데이터 소스를 생성합니다. |

### 비고

문서를 조립하는 동안 해당 파일 또는 스트림의 데이터에 접근하려면, 이 클래스의 인스턴스를 데이터 소스로 전달하여 [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 오버로드 중 하나에 사용합니다.

템플릿 문서에서, [`CsvDataSource`](../csvdatasource) 인스턴스는 DataTable 인스턴스인 것처럼 동일하게 취급해야 합니다. 자세한 내용은 템플릿 구문 참조(https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)를 참조하십시오.

쉼표로 구분된 값의 데이터 유형은 문자열 표현을 기반으로 자동으로 결정됩니다. 따라서 템플릿 문서에서는 문자열만이 아니라 형식이 지정된 값으로 작업할 수 있습니다. 엔진은 다음 유형의 값을 자동으로 인식할 수 있습니다:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

데이터 유형의 자동 인식이 작동하려면 쉼표로 구분된 값의 문자열 표현을 불변 문화 설정을 사용하여 형성해야 합니다.

CSV 데이터 로드의 기본 동작을 재정의하려면, [`CsvDataLoadOptions`](../csvdataloadoptions) 인스턴스를 초기화하여 이 클래스의 생성자에 전달하십시오.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
