---
title: JsonDataSource
second_title: Справочник по API GroupDocs.Assembly для .NET
description: Предоставляет доступ к данным файла или потока JSON для использования при сборке документа.
type: docs
weight: 150
url: /ru/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Предоставляет доступ к данным файла или потока JSON для использования при сборке документа.

```csharp
public class JsonDataSource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | Создает новый источник данных с данными из потока JSON, используя параметры по умолчанию для анализа данных JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | Создает новый источник данных с данными из файла JSON, используя параметры по умолчанию для анализа данных JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | Создает новый источник данных с данными из потока JSON, используя указанные параметры анализа данных JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | Создает новый источник данных с данными из файла JSON, используя указанные параметры анализа данных JSON. |

### Примечания

Чтобы получить доступ к данным соответствующего файла или потока при сборке документа, передайте экземпляр этого класса как источник данных одному из[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument перегружает.

В шаблонных документах, если элемент JSON верхнего уровня является массивом,[`JsonDataSource`](../jsondatasource) экземпляр должен быть обработан так же, как если бы он былDataTable пример. Если элемент JSON верхнего уровня является объектом,[`JsonDataSource`](../jsondatasource) Экземпляр следует рассматривать так же, как если бы он был aDataRowпример. Дополнительные сведения см. в справочнике по синтаксису шаблона (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

В шаблонных документах можно работать с типизированными значениями элементов JSON. Для удобства движок заменяет набор простых типов JSON на следующий:

* `длинный?`
* `двойной?`
* `буль?`
* `ДатаВремя?`
* `нить`

Движок автоматически распознает значения дополнительных типов по их представлениям JSON.

Чтобы переопределить поведение загрузки данных JSON по умолчанию, инициализируйте и передайте[`JsonDataLoadOptions`](../jsondataloadoptions)instance в конструктор этого класса.

### Смотрите также

* пространство имен [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* сборка [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
