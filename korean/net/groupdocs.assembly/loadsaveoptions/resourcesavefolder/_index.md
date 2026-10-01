---
title: "ResourceSaveFolder"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "조립된 문서를 비HTML 형식에서 로드한 후 HTML로 저장하는 동안 외부 리소스 파일을 저장할 폴더 경로를 가져오거나 설정합니다. 기본값은 빈 문자열입니다."
type: docs
weight: 30
url: /ko/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

비HTML 형식에서 로드된 조립 문서를 HTML로 저장하는 동안 외부 리소스 파일을 저장할 폴더 경로를 가져오거나 설정합니다. 기본값은 빈 문자열입니다.

```csharp
public string ResourceSaveFolder { get; set; }
```

### 비고

기본적으로 조립된 문서를 HTML 파일로 저장할 때 외부 리소스 파일은 HTML 파일 이름에서 확장자를 제외하고 "_files" 접미사를 붙인 동일한 이름의 폴더에 저장됩니다. 이 폴더는 HTML 파일과 같은 폴더에 위치합니다. 그러나 조립된 문서를 HTML 스트림으로 저장할 경우에는 이 방법을 사용할 수 없습니다. 이 속성을 설정하여 조립된 문서를 HTML 스트림으로 저장할 때 외부 리소스 파일을 저장할 폴더 경로를 지정하거나, HTML 파일로 저장할 때 기본 폴더를 재정의할 수 있습니다.

이 속성의 값은 HTML로 저장되는 조립된 문서가 HTML에서 로드된 경우 무시됩니다(외부 리소스 파일이 저장되지 않으며 해당 파일에 대한 링크도 변경되지 않습니다).

### 관련 항목

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
