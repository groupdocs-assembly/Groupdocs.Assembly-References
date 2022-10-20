---
title: SaveFormat
second_title: Справочник по API GroupDocs.Assembly для .NET
description: Получает или задает формат файла для сохранения собранного документа.Unspecified по умолчанию.
type: docs
weight: 40
url: /ru/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

Получает или задает формат файла для сохранения собранного документа.Unspecified по умолчанию.

```csharp
public FileFormat SaveFormat { get; set; }
```

### Примечания

Если значение этого свойства не указано,[`DocumentAssembler`](../../documentassembler) ведет себя следующим образом:

— когда вы указываете путь к файлу для сохранения собранного документа, формат файла сохранения определяется расширением файла из пути.

— когда вы указываете поток для сохранения собранного документа, формат файла сохранения остается таким же, как формат файла загруженного документа шаблона.

Учтите, что не всегда возможно сохранить собранный документ в файл любого формата с помощью GroupDocs.Assembly. Например, невозможно сохранить документ, загруженный из формата файла Word Processing (например, DOCX), в формата файла электронной таблицы (например, XLSX). Для получения дополнительной информации о возможных комбинациях форматов файлов загрузки и сохранения , поддерживаемых GroupDocs.Assembly, см. онлайн-документацию GroupDocs.Assembly.

### Смотрите также

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* пространство имен [GroupDocs.Assembly](../../loadsaveoptions)
* сборка [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->