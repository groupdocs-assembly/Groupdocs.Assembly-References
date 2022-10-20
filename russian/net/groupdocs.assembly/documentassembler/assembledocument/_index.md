---
title: AssembleDocument
second_title: Справочник по API GroupDocs.Assembly для .NET
description: Загружает документшаблон из указанного исходного пути заполняет документшаблон данными из указанного одного или нескольких источников и сохраняет результирующий документ по целевому пути используя default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /ru/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Загружает документ-шаблон из указанного исходного пути, заполняет документ-шаблон данными из указанного одного или нескольких источников и сохраняет результирующий документ по целевому пути, используя default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к документу шаблона, который будет заполнен данными. |
| targetPath | String | Путь к результирующему документу. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источника данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли разбор документа шаблона успешным. Возвращаемый флаг имеет смысл, только если значение[`Options`](../options) собственность включает в себяInlineErrorMessages опция.

### Смотрите также

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* пространство имен [GroupDocs.Assembly](../../documentassembler)
* сборка [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Загружает документ-шаблон из указанного исходного пути, заполняет документ-шаблон данными из указанного одного или нескольких источников и сохраняет результирующий документ по целевому пути, используя заданный [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к документу шаблона, который будет заполнен данными. |
| targetPath | String | Путь к результирующему документу. |
| loadSaveOptions | LoadSaveOptions | Указывает дополнительные параметры загрузки и сохранения документа. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источника данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли разбор документа шаблона успешным. Возвращаемый флаг имеет смысл, только если значение[`Options`](../options) собственность включает в себяInlineErrorMessages опция.

### Смотрите также

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* пространство имен [GroupDocs.Assembly](../../documentassembler)
* сборка [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Загружает документ шаблона из указанного исходного потока, заполняет документ шаблона данными из указанного одного или нескольких источников и сохраняет результирующий документ в целевом потоке, используя default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStream | Stream | Поток, из которого читается документ-шаблон. |
| targetStream | Stream | Поток для записи результирующего документа. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источника данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли разбор документа шаблона успешным. Возвращаемый флаг имеет смысл, только если значение[`Options`](../options) собственность включает в себяInlineErrorMessages опция.

### Смотрите также

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* пространство имен [GroupDocs.Assembly](../../documentassembler)
* сборка [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Загружает документ-шаблон из указанного исходного потока, заполняет документ-шаблон данными из указанного одного или нескольких источников и сохраняет результирующий документ в целевом потоке, используя заданный [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStream | Stream | Поток, из которого читается документ-шаблон. |
| targetStream | Stream | Поток для записи результирующего документа. |
| loadSaveOptions | LoadSaveOptions | Указывает дополнительные параметры загрузки и сохранения документа. |
| dataSourceInfos | DataSourceInfo[] | Предоставляет информацию об объектах источника данных, которые будут использоваться. |

### Возвращаемое значение

Флаг, указывающий, был ли разбор документа шаблона успешным. Возвращаемый флаг имеет смысл, только если значение[`Options`](../options) собственность включает в себяInlineErrorMessages опция.

### Смотрите также

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* пространство имен [GroupDocs.Assembly](../../documentassembler)
* сборка [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
