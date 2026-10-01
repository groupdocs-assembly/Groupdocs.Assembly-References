---
title: "LoadSaveOptions"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "조립될 문서를 로드하고 저장하기 위한 추가 옵션을 지정합니다."
type: docs
weight: 80
url: /ko/net/groupdocs.assembly/loadsaveoptions/
---
## LoadSaveOptions class

조립될 문서를 로드하고 저장하기 위한 추가 옵션을 지정합니다.

```csharp
public class LoadSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LoadSaveOptions](loadsaveoptions#constructor)() | 이 클래스의 새 인스턴스를 속성을 지정하지 않고 생성합니다. |
| [LoadSaveOptions](loadsaveoptions#constructor_1)(FileFormat) | 조립된 문서를 저장할 지정된 파일 형식으로 이 클래스의 새 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ResourceLoadBaseUri](../../groupdocs.assembly/loadsaveoptions/resourceloadbaseuri) { get; set; } | HTML 템플릿 문서를 로드하여 조립하고 비HTML 형식으로 저장하는 동안 외부 리소스 파일의 상대 URI를 절대 URI로 해결하기 위한 기본 URI를 가져오거나 설정합니다. 기본값은 빈 문자열입니다. |
| [ResourceSaveFolder](../../groupdocs.assembly/loadsaveoptions/resourcesavefolder) { get; set; } | 비HTML 형식에서 로드된 조립 문서를 HTML로 저장하는 동안 외부 리소스 파일을 저장할 폴더 경로를 가져오거나 설정합니다. 기본값은 빈 문자열입니다. |
| [SaveFormat](../../groupdocs.assembly/loadsaveoptions/saveformat) { get; set; } | 조립된 문서를 저장할 파일 형식을 가져오거나 설정합니다. 지정되지 않으면 기본값이 사용됩니다. |

### 관련 항목

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
