---
title: "JsonDataSource"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belge oluşturulurken kullanılacak JSON dosyası veya akışının verilerine erişim sağlar."
type: docs
weight: 230
url: /tr/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Bir belge oluşturulurken kullanılacak JSON dosyası veya akışının verilerine erişim sağlar.

```csharp
public class JsonDataSource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | JSON verilerini ayrıştırmak için varsayılan seçenekleri kullanarak bir JSON akışından veriyle yeni bir veri kaynağı oluşturur. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | JSON verilerini ayrıştırmak için varsayılan seçenekleri kullanarak bir JSON dosyasından veriyle yeni bir veri kaynağı oluşturur. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | JSON verilerini ayrıştırmak için belirtilen seçenekleri kullanarak bir JSON akışından veriyle yeni bir veri kaynağı oluşturur. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | JSON verilerini ayrıştırmak için belirtilen seçenekleri kullanarak bir JSON dosyasından veriyle yeni bir veri kaynağı oluşturur. |

### Açıklamalar

Bir belge birleştirirken ilgili dosya veya akışın verilerine erişmek için, bu sınıfın bir örneğini bir veri kaynağı olarak [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument aşırı yüklemelerinden birine geçirin.

Şablon belgelerinde, üst düzey JSON öğesi bir dizi ise, bir [`JsonDataSource`](../jsondatasource) örneği bir DataTable örneği gibi ele alınmalıdır. Üst düzey JSON öğesi bir nesne ise, bir [`JsonDataSource`](../jsondatasource) örneği bir DataRow örneği gibi ele alınmalıdır. Daha fazla bilgi için şablon sözdizimi referansına bakın (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Şablon belgelerinde, JSON öğelerinin tiplenmiş değerleriyle çalışabilirsiniz. Kolaylık sağlamak için, motor JSON basit tiplerinin kümesini aşağıdakiyle değiştirir:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Motor, ek tiplerin değerlerini JSON temsilleri üzerinden otomatik olarak tanır.

JSON veri yüklemesinin varsayılan davranışını geçersiz kılmak için, bir [`JsonDataLoadOptions`](../jsondataloadoptions) örneğini başlatın ve bu sınıfın yapıcısına geçirin.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
