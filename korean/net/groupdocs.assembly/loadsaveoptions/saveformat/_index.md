---
title: "SaveFormat"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "조립된 문서를 저장할 파일 형식을 가져오거나 설정합니다. 지정되지 않으면 기본값이 사용됩니다."
type: docs
weight: 40
url: /ko/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

조립된 문서를 저장할 파일 형식을 가져오거나 설정합니다. 지정되지 않으면 기본값이 사용됩니다.

```csharp
public FileFormat SaveFormat { get; set; }
```

### 비고

이 속성의 값이 지정되지 않은 경우, [`DocumentAssembler`](../../documentassembler) 는 다음과 같이 동작합니다:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

GroupDocs.Assembly를 사용하여 조립된 문서를 모든 파일 형식으로 저장할 수 있는 것은 아닙니다. 예를 들어, 워드 프로세싱 파일 형식(DOCX 등)에서 로드한 문서를 스프레드시트 파일 형식(XLSX 등)으로 저장하는 것은 불가능합니다. GroupDocs.Assembly에서 지원하는 로드 및 저장 파일 형식 조합에 대한 자세한 내용은 GroupDocs.Assembly 온라인 문서를 확인하십시오.

### 관련 항목

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
