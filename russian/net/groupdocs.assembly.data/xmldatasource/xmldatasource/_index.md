---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly для .NET API Reference"
description: "Создает новый источник данных с данными из XML‑файла, используя параметры по умолчанию для загрузки XML‑данных."
type: docs
weight: 10
url: /ru/net/groupdocs.assembly.data/xmldatasource/xmldatasource/
---
## XmlDataSource(string) {#constructor_4}

Создает новый источник данных с данными из XML‑файла, используя параметры по умолчанию для загрузки XML‑данных.

```csharp
public XmlDataSource(string xmlPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlPath | String | Путь к XML‑файлу, который будет использоваться в качестве источника данных. |

### См. также

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream) {#constructor}

Создает новый источник данных с данными из XML‑потока, используя параметры по умолчанию для загрузки XML‑данных.

```csharp
public XmlDataSource(Stream xmlStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | Stream | Поток XML‑данных, который будет использоваться в качестве источника данных. |

### См. также

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string) {#constructor_6}

Создает новый источник данных с данными из XML‑файла, используя файл определения XML‑схемы. Для загрузки XML‑данных используются параметры по умолчанию.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlPath | String | Путь к XML‑файлу, который будет использоваться в качестве источника данных. |
| xmlSchemaPath | String | Путь к файлу определения схемы XML (XSD), который предоставляет схему для XML‑файла. |

### См. также

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream) {#constructor_2}

Создает новый источник данных с данными из XML‑потока, используя поток определения схемы XML (XSD). Для загрузки XML‑данных используются параметры по умолчанию.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | Stream | Поток XML‑данных, который будет использоваться в качестве источника данных. |
| xmlSchemaStream | Stream | Поток определения схемы XML, который предоставляет схему для XML‑данных. |

### См. также

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, XmlDataLoadOptions) {#constructor_5}

Создает новый источник данных с данными из XML‑файла, используя указанные параметры загрузки XML‑данных.

```csharp
public XmlDataSource(string xmlPath, XmlDataLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlPath | String | Путь к XML‑файлу, который будет использоваться в качестве источника данных. |
| параметры | XmlDataLoadOptions | Параметры загрузки XML‑данных. |

### См. также

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, XmlDataLoadOptions) {#constructor_1}

Создает новый источник данных с данными из XML‑потока, используя указанные параметры загрузки XML‑данных.

```csharp
public XmlDataSource(Stream xmlStream, XmlDataLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | Stream | Поток XML‑данных, который будет использоваться в качестве источника данных. |
| параметры | XmlDataLoadOptions | Параметры загрузки XML‑данных. |

### См. также

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string, XmlDataLoadOptions) {#constructor_7}

Создает новый источник данных с данными из XML‑файла, используя файл определения XML‑схемы. Для загрузки XML‑данных используются указанные параметры.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath, XmlDataLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlPath | String | Путь к XML‑файлу, который будет использоваться в качестве источника данных. |
| xmlSchemaPath | String | Путь к файлу определения схемы XML (XSD), который предоставляет схему для XML‑файла. |
| параметры | XmlDataLoadOptions | Параметры загрузки XML‑данных. |

### См. также

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream, XmlDataLoadOptions) {#constructor_3}

Создает новый источник данных с данными из XML‑потока, используя поток определения XML‑схемы. Для загрузки XML‑данных используются указанные параметры.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream, XmlDataLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | Stream | Поток XML‑данных, который будет использоваться в качестве источника данных. |
| xmlSchemaStream | Stream | Поток определения схемы XML, который предоставляет схему для XML‑данных. |
| параметры | XmlDataLoadOptions | Параметры загрузки XML‑данных. |

### См. также

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
