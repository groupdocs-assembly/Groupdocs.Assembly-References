---
title: SetLicense
second_title: Справочник по API GroupDocs.Assembly для .NET
description: Лицензирует компонент.
type: docs
weight: 30
url: /ru/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Лицензирует компонент.

```csharp
public void SetLicense(string licenseName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | String | Может быть полным или коротким именем файла или именем внедренного ресурса. Используйте пустую строку для переключения в режим оценки. |

### Примечания

Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка, содержащая сборку компонента GroupDocs.

3. Папка, содержащая вызывающую сборку клиента.

4. Папка, содержащая входную (загрузочную) сборку.

5. Встроенный ресурс в вызывающей сборке клиента.

### Смотрите также

* class [License](../../license)
* пространство имен [GroupDocs.Assembly](../../license)
* сборка [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

Лицензирует компонент.

```csharp
public void SetLicense(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, содержащий лицензию. |

### Примечания

Используйте этот метод для загрузки лицензии из потока.

### Смотрите также

* class [License](../../license)
* пространство имен [GroupDocs.Assembly](../../license)
* сборка [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
