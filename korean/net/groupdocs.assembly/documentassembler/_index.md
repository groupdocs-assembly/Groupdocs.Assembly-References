---
title: "DocumentAssembler"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "데이터와 이러한 루틴을 제어하는 설정 집합으로 템플릿 문서를 채우는 루틴을 제공합니다."
type: docs
weight: 40
url: /ko/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

데이터와 이러한 루틴을 제어하는 설정 집합으로 템플릿 문서를 채우는 루틴을 제공합니다.

```csharp
public class DocumentAssembler
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DocumentAssembler](documentassembler)() | 이 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | 문서를 조립하는 동안 바코드 생성을 제어하는 설정 집합을 가져옵니다. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | 이 어셈블러 인스턴스가 처리하는 문서 템플릿 내에서 해당 유형의 정적 멤버를 호출하거나 형 변환 등을 수행하기 위해 완전하거나 부분적으로 지정된 이름을 사용할 수 있는 Type 객체를 포함하는 순서가 없는 집합(즉, 고유 항목의 컬렉션)을 가져옵니다. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | 이 [`DocumentAssembler`](../documentassembler) 인스턴스가 문서를 조립하는 동안 동작을 제어하는 플래그 집합을 가져오거나 설정합니다. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | 사용자 정의 형식 멤버를 리플렉션 API를 통해 호출할 때 동적 클래스 생성을 사용하여 최적화할지 여부를 나타내는 값을 가져오거나 설정합니다. 기본값은 true입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | 지정된 소스 스트림에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 기본 [`LoadSaveOptions`](../loadsaveoptions)를 사용하여 결과 문서를 대상 스트림에 저장합니다. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | 지정된 소스 경로에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 기본 [`LoadSaveOptions`](../loadsaveoptions)를 사용하여 결과 문서를 대상 경로에 저장합니다. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | 지정된 소스 스트림에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 제공된 [`LoadSaveOptions`](../loadsaveoptions)를 사용하여 결과 문서를 대상 스트림에 저장합니다. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | 지정된 소스 경로에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 제공된 [`LoadSaveOptions`](../loadsaveoptions)를 사용하여 결과 문서를 대상 경로에 저장합니다. |

### 관련 항목

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
