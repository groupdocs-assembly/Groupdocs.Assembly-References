---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly для .NET API Reference"
description: "Загружает шаблон документа из указанного пути источника, заполняет шаблон данными из указанного одного или нескольких источников и сохраняет полученный документ в целевой путь, используя параметры по умолчанию LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /ru/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Загружает шаблон документа из указанного пути источника, заполняет шаблон данными из указанного одного или нескольких источников и сохраняет полученный документ в целевой путь, используя параметры по умолчанию [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к шаблону документа, который будет заполнен данными. |
| targetPath | String | Путь к результирующему документу. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источников данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли успешно выполнен разбор шаблона документа. Возвращаемый флаг имеет смысл только если значение свойства [`Options`](../options) включает параметр InlineErrorMessages.

### См. также

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Загружает шаблон документа из указанного пути источника, заполняет шаблон данными из указанного одного или нескольких источников и сохраняет полученный документ в целевой путь, используя указанные [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к шаблону документа, который будет заполнен данными. |
| targetPath | String | Путь к результирующему документу. |
| loadSaveOptions | LoadSaveOptions | Указывает дополнительные параметры для загрузки и сохранения документа. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источников данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли успешно выполнен разбор шаблона документа. Возвращаемый флаг имеет смысл только если значение свойства [`Options`](../options) включает параметр InlineErrorMessages.

### См. также

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Загружает шаблон документа из указанного потока источника, заполняет шаблон данными из указанного одного или нескольких источников и сохраняет полученный документ в целевой поток, используя параметры по умолчанию [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStream | Stream | Поток для чтения шаблона документа. |
| targetStream | Stream | Поток для записи результирующего документа. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источников данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли успешно выполнен разбор шаблона документа. Возвращаемый флаг имеет смысл только если значение свойства [`Options`](../options) включает параметр InlineErrorMessages.

### См. также

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Загружает шаблон документа из указанного потока источника, заполняет шаблон данными из указанного одного или нескольких источников и сохраняет полученный документ в целевой поток, используя указанные [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStream | Stream | Поток для чтения шаблона документа. |
| targetStream | Stream | Поток для записи результирующего документа. |
| loadSaveOptions | LoadSaveOptions | Указывает дополнительные параметры для загрузки и сохранения документа. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источников данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли успешно выполнен разбор шаблона документа. Возвращаемый флаг имеет смысл только если значение свойства [`Options`](../options) включает параметр InlineErrorMessages.

### См. также

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
