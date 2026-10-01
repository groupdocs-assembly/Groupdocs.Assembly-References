---
title: "GroupDocs.Assembly.Data"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belge birleştirirken kullanılacak dış belge verilerine erişmek için sınıflar sağlar."
type: docs
weight: 20
url: /tr/net/groupdocs.assembly.data/
---
Bir belge birleştirirken kullanılacak dış belge verilerine erişmek için sınıflar sağlar.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | CSV verilerini ayrıştırmak için seçenekleri temsil eder. |
| [CsvDataSource](./csvdatasource) | Bir belge oluşturulurken kullanılacak CSV dosyası veya akışının verilerine erişim sağlar. |
| [DocumentTable](./documenttable) | Bir belge oluşturulurken kullanılacak dış bir belgede bulunan tek bir tablo (veya elektronik tablo) verilerine erişim sağlar. |
| [DocumentTableCollection](./documenttablecollection) | Belirli bir [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) örneğine ait [`DocumentTable`](../groupdocs.assembly.data/documenttable) nesnelerinin yalnızca okunabilir bir koleksiyonunu temsil eder. |
| [DocumentTableColumn](./documenttablecolumn) | Belirli bir [`DocumentTable`](../groupdocs.assembly.data/documenttable) nesnesinin tek bir sütununu temsil eder. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | Belirli bir [`DocumentTable`](../groupdocs.assembly.data/documenttable) örneğine ait [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) nesnelerinin yalnızca okunabilir bir koleksiyonunu temsil eder. |
| [DocumentTableLoadArgs](./documenttableloadargs) | [`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle) yöntemi için veri sağlar. |
| [DocumentTableOptions](./documenttableoptions) | Bir belge tablosundan veri çıkarımını kontrol etmek için bir dizi seçenek sağlar. |
| [DocumentTableRelation](./documenttablerelation) | İki [`DocumentTable`](../groupdocs.assembly.data/documenttable) nesnesi arasındaki ebeveyn-çocuk ilişkisinin temsilidir. |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | Tek bir [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) örneğine ait [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) nesnelerinin koleksiyonunu temsil eder. |
| [DocumentTableSet](./documenttableset) | Bir belge oluşturulurken kullanılacak dış bir belgede bulunan birden fazla tablo (veya elektronik tablo) verilerine erişim sağlar. Ayrıca, belge tabloları için ebeveyn-çocuk ilişkilerini tanımlamayı mümkün kılar ve böylece şablon belgeler içinde ilgili verilere erişimi basitleştirir. |
| [JsonDataLoadOptions](./jsondataloadoptions) | JSON verisinin ayrıştırılması için seçenekleri temsil eder. |
| [JsonDataSource](./jsondatasource) | Bir belge oluşturulurken kullanılacak JSON dosyası veya akışının verilerine erişim sağlar. |
| [XmlDataLoadOptions](./xmldataloadoptions) | XML veri yüklemesi için seçenekleri temsil eder. |
| [XmlDataSource](./xmldatasource) | Bir belge oluşturulurken kullanılacak XML dosyası veya akışının verilerine erişim sağlar. |
## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | `[`DocumentTable`](../groupdocs.assembly.data/documenttable)` nesnelerinin varsayılan yüklemesini, bir [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) örneği oluşturulurken geçersiz kılar. |
## Sıralama

| Sıralama | Açıklama |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | JSON yüklenirken JSON basit değerlerini (null, boolean, sayı, tam sayı ve dize) ayrıştırmak için bir mod belirtir. Böyle bir mod tarih‑zaman değerlerinin ayrıştırılmasını etkilemez. |

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
