---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 사용할 XML 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다."
type: docs
weight: 260
url: /ko/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

문서를 조립하는 동안 사용할 XML 파일 또는 스트림의 데이터에 대한 액세스를 제공합니다.

```csharp
public class XmlDataSource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | XML 스트림의 데이터를 사용하고 XML 데이터 로드를 위한 기본 옵션으로 새 데이터 소스를 생성합니다. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | XML 파일의 데이터를 사용하고 XML 데이터 로드를 위한 기본 옵션으로 새 데이터 소스를 생성합니다. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | XML 스키마 정의 스트림을 사용하여 XML 스트림의 데이터를 기반으로 새 데이터 소스를 생성합니다. XML 데이터 로드에는 기본 옵션이 사용됩니다. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | 지정된 XML 데이터 로드 옵션을 사용하여 XML 스트림의 데이터를 포함하는 새 데이터 소스를 생성합니다. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | XML 스키마 정의 파일을 사용하여 XML 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다. XML 데이터 로드에는 기본 옵션이 사용됩니다. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | 지정된 XML 데이터 로드 옵션을 사용하여 XML 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | XML 스키마 정의 스트림을 사용하여 XML 스트림의 데이터를 포함하는 새 데이터 소스를 생성합니다. 지정된 옵션이 XML 데이터 로드에 사용됩니다. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | XML 스키마 정의 파일을 사용하여 XML 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다. 지정된 옵션이 XML 데이터 로드에 사용됩니다. |

### 비고

문서를 조립하는 동안 해당 파일 또는 스트림의 데이터에 접근하려면, 이 클래스의 인스턴스를 데이터 소스로 전달하여 [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 오버로드 중 하나에 사용합니다.

템플릿 문서에서 최상위 XML 요소가 동일한 유형의 요소 목록만 포함하는 경우, [`XmlDataSource`](../xmldatasource) 인스턴스를 DataTable 인스턴스처럼 취급해야 합니다. 그렇지 않은 경우, [`XmlDataSource`](../xmldatasource) 인스턴스를 DataRow 인스턴스처럼 취급해야 합니다. 자세한 내용은 템플릿 구문 참조(https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)를 확인하십시오.

XML 스키마 정의가 이 클래스의 생성자에 전달되면 단순 XML 요소와 속성 값의 데이터 유형이 스키마에 따라 결정됩니다. 따라서 템플릿 문서에서 문자열 대신 형식이 지정된 값을 사용할 수 있습니다.

XML 스키마 정의가 이 클래스의 생성자에 전달되지 않으면 단순 XML 요소와 속성 값의 데이터 유형이 문자열 표현을 기반으로 자동으로 결정됩니다. 따라서 템플릿 문서에서도 이 경우 형식이 지정된 값을 사용할 수 있습니다. 엔진은 다음 유형의 값을 자동으로 인식할 수 있습니다:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

데이터 유형의 자동 인식이 작동하려면 단순 XML 요소와 속성 값의 문자열 표현이 불변 문화 설정을 사용하여 형성되어야 합니다.

XML 데이터 로드의 기본 동작을 재정의하려면 [`XmlDataLoadOptions`](../xmldataloadoptions) 인스턴스를 초기화하여 이 클래스의 생성자에 전달하십시오.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
