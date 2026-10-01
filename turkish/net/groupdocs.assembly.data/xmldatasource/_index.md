---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belge oluşturulurken kullanılacak XML dosyası veya akışının verilerine erişim sağlar."
type: docs
weight: 260
url: /tr/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

Bir belge oluşturulurken kullanılacak XML dosyası veya akışının verilerine erişim sağlar.

```csharp
public class XmlDataSource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | XML akışından gelen verilerle, XML veri yüklemesi için varsayılan seçenekleri kullanarak yeni bir veri kaynağı oluşturur. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | XML dosyasından gelen verilerle, XML veri yüklemesi için varsayılan seçenekleri kullanarak yeni bir veri kaynağı oluşturur. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | XML akışından gelen verilerle bir XML Şema Tanımı akışı kullanarak yeni bir veri kaynağı oluşturur. XML veri yüklemesi için varsayılan seçenekler kullanılır. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | Belirtilen XML veri yükleme seçeneklerini kullanarak bir XML akışından veri ile yeni bir veri kaynağı oluşturur. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | Bir XML Şema Tanımı dosyası kullanarak bir XML dosyasından veri ile yeni bir veri kaynağı oluşturur. XML veri yüklemesi için varsayılan seçenekler kullanılır. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | Belirtilen XML veri yükleme seçeneklerini kullanarak bir XML dosyasından veri ile yeni bir veri kaynağı oluşturur. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | Bir XML Şema Tanımı akışı kullanarak bir XML akışından veri ile yeni bir veri kaynağı oluşturur. Belirtilen seçenekler XML veri yüklemesi için kullanılır. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | Bir XML Şema Tanımı dosyası kullanarak bir XML dosyasından veri ile yeni bir veri kaynağı oluşturur. Belirtilen seçenekler XML veri yüklemesi için kullanılır. |

### Açıklamalar

Bir belge birleştirirken ilgili dosya veya akışın verilerine erişmek için, bu sınıfın bir örneğini bir veri kaynağı olarak [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument aşırı yüklemelerinden birine geçirin.

Şablon belgelerinde, üst düzey bir XML öğesi yalnızca aynı türde öğelerin bir listesini içeriyorsa, bir [`XmlDataSource`](../xmldatasource) örneği bir DataTable örneği gibi ele alınmalıdır. Aksi takdirde, bir [`XmlDataSource`](../xmldatasource) örneği bir DataRow örneği gibi ele alınmalıdır. Daha fazla bilgi için şablon sözdizimi referansına bakın (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Bu sınıfın yapıcısına bir XML Şema Tanımı geçirildiğinde, basit XML öğeleri ve özniteliklerinin değer tipleri şemaya göre belirlenir. Böylece şablon belgelerinde yalnızca dizeler yerine tiplenmiş değerlerle çalışabilirsiniz.

Bu sınıfın yapıcısına bir XML Şema Tanımı geçirilmediğinde, basit XML öğeleri ve özniteliklerinin değer tiplerinin dizge temsilleri üzerinden otomatik olarak belirlenir. Böylece şablon belgelerinde bu durumda da tiplenmiş değerlerle çalışabilirsiniz. Motor aşağıdaki tipteki değerleri otomatik olarak tanıyabilir:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Veri tiplerinin otomatik olarak tanınabilmesi için, basit XML öğeleri ve özniteliklerinin değerlerinin dizge temsillerinin değişmez kültür ayarları kullanılarak oluşturulması gerektiğini unutmayın.

XML veri yüklemesinin varsayılan davranışını geçersiz kılmak için bir [`XmlDataLoadOptions`](../xmldataloadoptions) örneği başlatın ve bu sınıfın yapıcısına geçirin.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
