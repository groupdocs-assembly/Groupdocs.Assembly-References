---
title: "ResourceLoadBaseUri"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "HTML 템플릿 문서를 로드하여 조립하고 비HTML 형식으로 저장하는 동안 외부 리소스 파일의 상대 URI를 절대 URI로 변환하기 위한 기본 URI를 가져오거나 설정합니다. 기본값은 빈 문자열입니다."
type: docs
weight: 20
url: /ko/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

HTML 템플릿 문서를 로드하여 조립하고 비HTML 형식으로 저장하는 동안 외부 리소스 파일의 상대 URI를 절대 URI로 해결하기 위한 기본 URI를 가져오거나 설정합니다. 기본값은 빈 문자열입니다.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### 비고

파일에서 HTML 문서를 로드할 때 기본적으로 포함 폴더가 기본 URI로 사용되지만, 스트림에서 HTML 문서를 로드할 때는 사용할 수 없습니다. 이 속성을 설정하여 스트림에서 HTML 문서를 로드할 때 기본 URI를 지정하거나 파일에서 HTML 문서를 로드할 때 기본 URI를 재정의할 수 있습니다.

다음 경우에는 이 속성의 값이 무시됩니다:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### 관련 항목

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
