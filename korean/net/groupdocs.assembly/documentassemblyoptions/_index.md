---
title: "DocumentAssemblyOptions"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 DocumentAssembler./documentassembler의 동작을 제어하는 옵션을 지정합니다."
type: docs
weight: 50
url: /ko/net/groupdocs.assembly/documentassemblyoptions/
---
## DocumentAssemblyOptions enumeration

문서를 조립하는 동안 [`DocumentAssembler`](../documentassembler)의 동작을 제어하는 옵션을 지정합니다.

```csharp
[Flags]
public enum DocumentAssemblyOptions
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 기본 옵션을 지정합니다. |
| AllowMissingMembers | `1` | 누락된 객체 멤버를 어셈블러가 null 리터럴로 처리하도록 지정합니다. 이 옵션은 인스턴스(즉, 비정적) 객체 멤버와 확장 메서드에 대한 접근에만 영향을 미칩니다. 이 옵션이 설정되지 않으면, 어셈블러는 누락된 객체 멤버를 만나면 예외를 발생시킵니다. |
| UpdateFieldsAndFormulas | `2` | 결과 워드 프로세싱 문서의 필드와 결과 스프레드시트 문서의 수식이 어셈블러에 의해 업데이트되도록 지정합니다. |
| RemoveEmptyParagraphs | `4` | 템플릿 구문 태그가 제거되거나 빈 값으로 교체된 후 빈 문단이 되는 경우 어셈블러가 해당 문단을 제거하도록 지정합니다. |
| InlineErrorMessages | `8` | 어셈블러가 템플릿 구문 오류 메시지를 출력 문서에 인라인하도록 지정합니다. 이 옵션이 설정되지 않으면 어셈블러는 구문 오류를 만나면 예외를 발생시킵니다. |
| UseSpreadsheetDataTypes | `10` | 스프레드시트 문서에만 적용됩니다. 평가된 식 결과를 해당 스프레드시트 데이터 유형에 매핑하도록 지정하며, 이는 셀 내 기본 서식에도 영향을 줍니다. 이 옵션이 설정되지 않으면 식 결과는 항상 문자열로 어셈블러에 의해 기록됩니다. 이 옵션은 템플릿 구문을 사용하여 식 결과를 서식 지정할 때는 영향을 주지 않으며, 그 경우에도 식 결과는 항상 문자열로 기록됩니다. |

### 관련 항목

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
