---
title: JsonSimpleValueParseMode
second_title: Справочник по API GroupDocs.Assembly для .NET
description: Определяет режим анализа простых значений JSON null boolean number integer и string при загрузке JSON. Такой режим не влияет на синтаксический анализ значений даты и времени.
type: docs
weight: 160
url: /ru/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

Определяет режим анализа простых значений JSON (null, boolean, number, integer и string) при загрузке JSON. Такой режим не влияет на синтаксический анализ значений даты и времени.

```csharp
public enum JsonSimpleValueParseMode
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Loose | `0` | Указывает режим, в котором типы простых значений JSON определяются при разборе их строковых представлений. Например, тип 'prop' из фрагмента JSON '{ prop: "123" }' в этом режиме определяется как целое число. |
| Strict | `1` | Указывает режим, в котором типы простых значений JSON определяются из самой нотации JSON. |

### Смотрите также

* пространство имен [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* сборка [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
