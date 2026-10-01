---
title: "CsvDataSource"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belge oluşturulurken kullanılacak CSV dosyası veya akışının verilerine erişim sağlar."
type: docs
weight: 110
url: /tr/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

Bir belge oluşturulurken kullanılacak CSV dosyası veya akışının verilerine erişim sağlar.

```csharp
public class CsvDataSource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | CSV akışından gelen verilerle, CSV verilerini ayrıştırmak için varsayılan seçenekleri kullanarak yeni bir veri kaynağı oluşturur. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | CSV dosyasından gelen verilerle, CSV verilerini ayrıştırmak için varsayılan seçenekleri kullanarak yeni bir veri kaynağı oluşturur. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | CSV akışından gelen verilerle, CSV verilerini ayrıştırmak için belirtilen seçenekleri kullanarak yeni bir veri kaynağı oluşturur. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | CSV dosyasından gelen verilerle, CSV verilerini ayrıştırmak için belirtilen seçenekleri kullanarak yeni bir veri kaynağı oluşturur. |

### Açıklamalar

Bir belge birleştirirken ilgili dosya veya akışın verilerine erişmek için, bu sınıfın bir örneğini bir veri kaynağı olarak [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument aşırı yüklemelerinden birine geçirin.

Şablon belgelerinde, bir [`CsvDataSource`](../csvdatasource) örneği, bir DataTable örneğiymiş gibi aynı şekilde ele alınmalıdır. Daha fazla bilgi için şablon sözdizimi referansına bakın (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Virgülle ayrılmış değerlerin veri tipleri, dize temsilleri üzerinden otomatik olarak belirlenir. Bu nedenle şablon belgelerinde yalnızca dizeler yerine tiplenmiş değerlerle çalışabilirsiniz. Motor, aşağıdaki tipteki değerleri otomatik olarak tanıyabilir:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Veri tiplerinin otomatik olarak tanınabilmesi için, virgülle ayrılmış değerlerin dize temsillerinin değişmez kültür ayarları kullanılarak oluşturulması gerektiğini unutmayın.

CSV veri yüklemesinin varsayılan davranışını geçersiz kılmak için, bir [`CsvDataLoadOptions`](../csvdataloadoptions) örneğini başlatın ve bu sınıfın yapıcısına geçirin.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
