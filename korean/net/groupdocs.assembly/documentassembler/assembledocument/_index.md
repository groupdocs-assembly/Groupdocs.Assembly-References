---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "지정된 소스 경로에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 기본 LoadSaveOptionsgroupdocs.assembly/loadsaveoptions를 사용하여 결과 문서를 대상 경로에 저장합니다."
type: docs
weight: 50
url: /ko/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

지정된 소스 경로에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 기본 [`LoadSaveOptions`](../../loadsaveoptions)를 사용하여 결과 문서를 대상 경로에 저장합니다.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | 데이터로 채워질 템플릿 문서의 경로입니다. |
| targetPath | String | 결과 문서의 경로입니다. |
| dataSourceInfos | DataSourceInfo[] | 사용될 데이터 소스 객체에 대한 정보를 제공합니다. |

### 반환 값

템플릿 문서의 구문 분석이 성공했는지 여부를 나타내는 플래그입니다. 반환된 플래그는 [`Options`](../options) 속성의 값에 InlineErrorMessages 옵션이 포함된 경우에만 의미가 있습니다.

### 관련 항목

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

지정된 소스 경로에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 제공된 [`LoadSaveOptions`](../../loadsaveoptions)를 사용하여 결과 문서를 대상 경로에 저장합니다.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | 데이터로 채워질 템플릿 문서의 경로입니다. |
| targetPath | String | 결과 문서의 경로입니다. |
| loadSaveOptions | LoadSaveOptions | 문서 로드 및 저장을 위한 추가 옵션을 지정합니다. |
| dataSourceInfos | DataSourceInfo[] | 사용될 데이터 소스 객체에 대한 정보를 제공합니다. |

### 반환 값

템플릿 문서의 구문 분석이 성공했는지 여부를 나타내는 플래그입니다. 반환된 플래그는 [`Options`](../options) 속성의 값에 InlineErrorMessages 옵션이 포함된 경우에만 의미가 있습니다.

### 관련 항목

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

지정된 소스 스트림에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 기본 [`LoadSaveOptions`](../../loadsaveoptions)를 사용하여 결과 문서를 대상 스트림에 저장합니다.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceStream | Stream | 템플릿 문서를 읽어올 스트림입니다. |
| targetStream | Stream | 결과 문서를 쓸 스트림입니다. |
| dataSourceInfos | DataSourceInfo[] | 사용될 데이터 소스 객체에 대한 정보를 제공합니다. |

### 반환 값

템플릿 문서의 구문 분석이 성공했는지 여부를 나타내는 플래그입니다. 반환된 플래그는 [`Options`](../options) 속성의 값에 InlineErrorMessages 옵션이 포함된 경우에만 의미가 있습니다.

### 관련 항목

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

지정된 소스 스트림에서 템플릿 문서를 로드하고, 지정된 단일 또는 다중 소스의 데이터로 템플릿 문서를 채운 다음, 제공된 [`LoadSaveOptions`](../../loadsaveoptions)를 사용하여 결과 문서를 대상 스트림에 저장합니다.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceStream | Stream | 템플릿 문서를 읽어올 스트림입니다. |
| targetStream | Stream | 결과 문서를 쓸 스트림입니다. |
| loadSaveOptions | LoadSaveOptions | 문서 로드 및 저장을 위한 추가 옵션을 지정합니다. |
| dataSourceInfos | DataSourceInfo[] | 사용될 데이터 소스 객체에 대한 정보를 제공합니다. |

### 반환 값

템플릿 문서의 구문 분석이 성공했는지 여부를 나타내는 플래그입니다. 반환된 플래그는 [`Options`](../options) 속성의 값에 InlineErrorMessages 옵션이 포함된 경우에만 의미가 있습니다.

### 관련 항목

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
