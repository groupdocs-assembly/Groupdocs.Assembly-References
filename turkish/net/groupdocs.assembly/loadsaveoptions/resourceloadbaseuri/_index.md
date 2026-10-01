---
title: "ResourceLoadBaseUri"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir HTML şablon belgesi yüklenirken dış kaynak dosyalarının göreli URI'larını mutlak URI'lara dönüştürmek için temel bir URI alır veya ayarlar; bu belge birleştirilip HTML dışı bir biçimde kaydedilir. Varsayılan değer boş bir dizedir."
type: docs
weight: 20
url: /tr/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

Birleştirilecek ve HTML dışı bir biçime kaydedilecek bir HTML şablon belgesi yüklenirken dış kaynak dosyalarının göreceli URI'larını mutlak URI'lara dönüştürmek için temel URI'yi alır veya ayarlar. Varsayılan değer boş bir dizedir.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### Açıklamalar

Bir HTML belgesi bir dosyadan yüklendiğinde, varsayılan olarak içeren klasör temel URI olarak kullanılır; bu durum bir HTML belgesi bir akıştan yüklendiğinde gerçekleşmez. Bu özelliği, bir HTML belgesi bir akıştan yüklendiğinde temel URI belirtmek veya bir dosyadan yüklendiğinde varsayılan temel URI'yı geçersiz kılmak için ayarlayın.

Bu özelliğin bir değeri aşağıdaki durumlarda yok sayılır:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### Ayrıca Bakınız

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
