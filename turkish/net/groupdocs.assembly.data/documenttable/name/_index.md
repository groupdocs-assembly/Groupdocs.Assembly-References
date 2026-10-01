---
title: "Ad"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bu tablonun adını alır veya ayarlar; bu ad, DocumentAssemblergroupdocs.assembly/documentassembler'a geçirilen bir şablon belgedeki tablonun verilerine erişmek için kullanılır."
type: docs
weight: 40
url: /tr/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

Bu tablonun adını alır veya ayarlar; bu ad, [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler)'a geçirilen bir şablon belgedeki tablonun verilerine erişmek için kullanılır.

```csharp
public string Name { get; set; }
```

### Açıklamalar

Tablonun adı bir belgeden okunursa, ad otomatik olarak geçerli olacak şekilde düzeltilir. Ancak, bu özellik aracılığıyla tablo adı manuel olarak ayarlanır ve ad geçersizse bir istisna fırlatılır.

Aşağıdaki koşullar karşılanıyorsa tablo adı geçerli kabul edilir:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### Ayrıca Bakınız

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
