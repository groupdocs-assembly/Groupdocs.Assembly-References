---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "XML 파일의 데이터를 사용하고 XML 데이터 로드를 위한 기본 옵션으로 새 데이터 소스를 생성합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.assembly.data/xmldatasource/xmldatasource/
---
## XmlDataSource(string) {#constructor_4}

XML 파일의 데이터를 사용하고 XML 데이터 로드를 위한 기본 옵션으로 새 데이터 소스를 생성합니다.

```csharp
public XmlDataSource(string xmlPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlPath | String | 데이터 소스로 사용할 XML 파일의 경로. |

### 관련 항목

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream) {#constructor}

XML 스트림의 데이터를 사용하고 XML 데이터 로드를 위한 기본 옵션으로 새 데이터 소스를 생성합니다.

```csharp
public XmlDataSource(Stream xmlStream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlStream | Stream | 데이터 소스로 사용할 XML 데이터 스트림. |

### 관련 항목

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string) {#constructor_6}

XML 스키마 정의 파일을 사용하여 XML 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다. XML 데이터 로드에는 기본 옵션이 사용됩니다.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlPath | String | 데이터 소스로 사용할 XML 파일의 경로. |
| xmlSchemaPath | String | XML 파일에 대한 스키마를 제공하는 XML 스키마 정의 파일의 경로. |

### 관련 항목

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream) {#constructor_2}

XML 스키마 정의 스트림을 사용하여 XML 스트림의 데이터를 기반으로 새 데이터 소스를 생성합니다. XML 데이터 로드에는 기본 옵션이 사용됩니다.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlStream | Stream | 데이터 소스로 사용할 XML 데이터 스트림. |
| xmlSchemaStream | Stream | XML 데이터에 대한 스키마를 제공하는 XML 스키마 정의 스트림. |

### 관련 항목

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, XmlDataLoadOptions) {#constructor_5}

지정된 XML 데이터 로드 옵션을 사용하여 XML 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다.

```csharp
public XmlDataSource(string xmlPath, XmlDataLoadOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlPath | String | 데이터 소스로 사용할 XML 파일의 경로. |
| 옵션 | XmlDataLoadOptions | XML 데이터 로드 옵션. |

### 관련 항목

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, XmlDataLoadOptions) {#constructor_1}

지정된 XML 데이터 로드 옵션을 사용하여 XML 스트림의 데이터를 포함하는 새 데이터 소스를 생성합니다.

```csharp
public XmlDataSource(Stream xmlStream, XmlDataLoadOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlStream | Stream | 데이터 소스로 사용할 XML 데이터 스트림. |
| 옵션 | XmlDataLoadOptions | XML 데이터 로드 옵션. |

### 관련 항목

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string, XmlDataLoadOptions) {#constructor_7}

XML 스키마 정의 파일을 사용하여 XML 파일의 데이터를 포함하는 새 데이터 소스를 생성합니다. 지정된 옵션이 XML 데이터 로드에 사용됩니다.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath, XmlDataLoadOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlPath | String | 데이터 소스로 사용할 XML 파일의 경로. |
| xmlSchemaPath | String | XML 파일에 대한 스키마를 제공하는 XML 스키마 정의 파일의 경로. |
| 옵션 | XmlDataLoadOptions | XML 데이터 로드 옵션. |

### 관련 항목

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream, XmlDataLoadOptions) {#constructor_3}

XML 스키마 정의 스트림을 사용하여 XML 스트림의 데이터를 포함하는 새 데이터 소스를 생성합니다. 지정된 옵션이 XML 데이터 로드에 사용됩니다.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream, XmlDataLoadOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlStream | Stream | 데이터 소스로 사용할 XML 데이터 스트림. |
| xmlSchemaStream | Stream | XML 데이터에 대한 스키마를 제공하는 XML 스키마 정의 스트림. |
| 옵션 | XmlDataLoadOptions | XML 데이터 로드 옵션. |

### 관련 항목

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
