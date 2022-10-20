---
title: ResourceLoadBaseUri
second_title: Справочник по API GroupDocs.Assembly для .NET
description: Получает или задает базовый URI для преобразования относительных URI файлов внешних ресурсов в абсолютные при загрузке документа шаблона HTML для сборки и сохранения в формате отличном от HTML. Значение по умолчанию  пустая строка.
type: docs
weight: 20
url: /ru/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

Получает или задает базовый URI для преобразования относительных URI файлов внешних ресурсов в абсолютные при загрузке документа шаблона HTML для сборки и сохранения в формате, отличном от HTML. Значение по умолчанию — пустая строка.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### Примечания

При загрузке HTML-документа из файла содержащая его папка используется в качестве базового URI по умолчанию, что не может произойти при загрузке HTML-документа из потока. Задайте это свойство, чтобы указать базовый URI при загрузке документа HTML из потока или переопределить базовый URI по умолчанию при загрузке документа HTML из файла.

Значение этого свойства игнорируется в следующих случаях:

* Загружаемый HTML-документ содержит элемент BASE HTML, предоставляющий базовый URI.
* Загружаемый HTML-документ должен быть собран и сохранен в HTML (внешние файлы ресурсов не загружаются и относительные URI не изменяются).

### Смотрите также

* class [LoadSaveOptions](../../loadsaveoptions)
* пространство имен [GroupDocs.Assembly](../../loadsaveoptions)
* сборка [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->