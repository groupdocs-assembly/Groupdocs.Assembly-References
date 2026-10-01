---
title: "Ad"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bu sütunun, DocumentAssemblergroupdocs.assembly/documentassembler'a geçirilen bir şablon belgede sütun verilerine erişmek için kullanılan adını alır veya ayarlar."
type: docs
weight: 30
url: /tr/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

Bu sütunun, [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler)'a geçirilen bir şablon belgede sütun verilerine erişmek için kullanılan adını alır veya ayarlar.

```csharp
public string Name { get; set; }
```

### Açıklamalar

Sütun adı bir belgeden okunursa (bkz. [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames)), ad otomatik olarak geçerli olacak şekilde düzeltilir. Ancak, bu özellik aracılığıyla sütun adı manuel olarak ayarlanır ve ad geçersizse bir istisna fırlatılır.

Aşağıdaki koşullar karşılandığında sütun adı geçerli kabul edilir:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### Ayrıca Bakınız

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
