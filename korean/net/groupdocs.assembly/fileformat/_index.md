---
title: "FileFormat"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "파일 형식을 지정합니다."
type: docs
weight: 30
url: /ko/net/groupdocs.assembly/fileformat/
---
## FileFormat enumeration

파일 형식을 지정합니다.

```csharp
public enum FileFormat
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Unspecified | `0` | 설정되지 않은 값을 지정합니다. 기본값입니다. |
| Doc | `1` | Microsoft Word 97 - 2007 바이너리 문서 형식을 지정합니다. |
| Dot | `2` | Microsoft Word 97 - 2007 바이너리 템플릿 형식을 지정합니다. |
| Docx | `3` | Office Open XML WordprocessingML 문서(매크로 없음) 형식을 지정합니다. |
| Docm | `4` | Office Open XML WordprocessingML 매크로 사용 문서 형식을 지정합니다. |
| Dotx | `5` | Office Open XML WordprocessingML 템플릿(매크로 없음) 형식을 지정합니다. |
| Dotm | `6` | Office Open XML WordprocessingML 매크로 사용 템플릿 형식을 지정합니다. |
| FlatOpc | `7` | ZIP 패키지 대신 플랫 XML 파일에 저장된 Office Open XML WordprocessingML 형식을 지정합니다. |
| FlatOpcMacroEnabled | `8` | ZIP 패키지 대신 플랫 XML 파일에 저장된 Office Open XML WordprocessingML 매크로 사용 문서 형식을 지정합니다. |
| FlatOpcTemplate | `9` | ZIP 패키지 대신 플랫 XML 파일에 저장된 Office Open XML WordprocessingML 템플릿(매크로 없음) 형식을 지정합니다. |
| FlatOpcTemplateMacroEnabled | `10` | ZIP 패키지 대신 평면 XML 파일에 저장된 Office Open XML WordprocessingML 매크로 사용 템플릿 형식을 지정합니다. |
| WordML | `11` | Microsoft Word 2003 WordprocessingML 형식을 지정합니다. |
| Odt | `12` | ODF 텍스트 문서 형식을 지정합니다. |
| Ott | `13` | ODF 텍스트 문서 템플릿 형식을 지정합니다. |
| Xls | `14` | Microsoft Excel 97 - 2007 바이너리 워크북 형식을 지정합니다. |
| Xlsx | `15` | Office Open XML SpreadsheetML 워크북(매크로 없음) 형식을 지정합니다. |
| Xlsm | `16` | Office Open XML SpreadsheetML 매크로 사용 워크북 형식을 지정합니다. |
| Xltx | `17` | Office Open XML SpreadsheetML 템플릿(매크로 없음) 형식을 지정합니다. |
| Xltm | `18` | Office Open XML SpreadsheetML 매크로 사용 템플릿 형식을 지정합니다. |
| Xlam | `19` | Office Open XML SpreadsheetML 매크로 사용 추가 기능 형식을 지정합니다. |
| Xlsb | `20` | Microsoft Excel 2007 매크로 사용 바이너리 파일 형식을 지정합니다. |
| SpreadsheetML | `21` | Microsoft Excel 2003 SpreadsheetML 형식을 지정합니다. |
| Ods | `22` | ODF 스프레드시트 형식을 지정합니다. |
| Ppt | `23` | Microsoft PowerPoint 97 - 2007 바이너리 프레젠테이션 형식을 지정합니다. |
| Pps | `24` | Microsoft PowerPoint 97 - 2007 바이너리 슬라이드 쇼 형식을 지정합니다. |
| Pptx | `25` | Office Open XML PresentationML 프레젠테이션(매크로 없음) 형식을 지정합니다. |
| Pptm | `26` | Office Open XML PresentationML 매크로 사용 프레젠테이션 형식을 지정합니다. |
| Ppsx | `27` | Office Open XML PresentationML 슬라이드 쇼(매크로 없음) 형식을 지정합니다. |
| Ppsm | `28` | Office Open XML PresentationML 매크로 사용 슬라이드 쇼 형식을 지정합니다. |
| Potx | `29` | Office Open XML PresentationML 템플릿(매크로 없음) 형식을 지정합니다. |
| Potm | `30` | Office Open XML PresentationML 매크로 사용 템플릿 형식을 지정합니다. |
| Odp | `31` | ODF 프레젠테이션 형식을 지정합니다. |
| MsgAscii | `32` | ASCII 문자 인코딩을 사용하는 Microsoft Outlook Message (MSG) 형식을 지정합니다. |
| MsgUnicode | `33` | Unicode 문자 인코딩을 사용하는 Microsoft Outlook Message (MSG) 형식을 지정합니다. |
| Eml | `34` | MIME 표준 형식을 지정합니다. |
| Emlx | `35` | Apple Mail.app 프로그램 파일 형식을 지정합니다. |
| Rtf | `36` | RTF 형식을 지정합니다. |
| Text | `37` | 일반 텍스트 형식을 지정합니다. |
| Xml | `38` | 일반 양식의 XML 형식을 지정합니다. |
| Xaml | `39` | 확장 응용 프로그램 마크업 언어 (XAML) 형식을 지정합니다. |
| XamlPackage | `40` | 확장 응용 프로그램 마크업 언어 (XAML) 패키지 형식을 지정합니다. |
| Html | `41` | HTML 형식을 지정합니다. |
| Mhtml | `42` | MHTML (웹 아카이브) 형식을 지정합니다. |
| Xps | `43` | XPS (XML Paper Specification) 형식을 지정합니다. |
| OpenXps | `44` | OpenXPS (Ecma-388) 형식을 지정합니다. |
| Pdf | `45` | PDF (Adobe Portable Document) 형식을 지정합니다. |
| Epub | `46` | IDPF EPUB 형식을 지정합니다. |
| Ps | `47` | PS (PostScript) 형식을 지정합니다. |
| Pcl | `48` | PCL (Printer Control Language) 형식을 지정합니다. |
| Svg | `49` | SVG (Scalable Vector Graphics) 형식을 지정합니다. |
| Tiff | `50` | TIFF 형식을 지정합니다. |
| Markdown | `51` | Markdown 형식을 지정합니다. |
| Pot | `52` | Microsoft PowerPoint 97 - 2007 바이너리 템플릿 형식을 지정합니다. |
| Otp | `53` | ODF 프레젠테이션 템플릿 형식을 지정합니다. |
| Xlt | `54` | Microsoft Excel 97 - 2007 바이너리 템플릿 형식을 지정합니다. |

### 관련 항목

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
