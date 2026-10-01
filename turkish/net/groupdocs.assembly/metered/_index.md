---
title: "Ölçümlü"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Ölçülen lisanslama ile çalışmak için yöntemler sağlar."
type: docs
weight: 90
url: /tr/net/groupdocs.assembly/metered/
---
## Metered class

Ölçülen lisanslama ile çalışmak için yöntemler sağlar.

```csharp
public class Metered
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Metered](metered)() | Bu sınıfın yeni bir örneğini oluşturur. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | Bileşen için uygun genel ve özel ölçümlü anahtarları belirterek ölçümlü lisanslamayı etkinleştirir. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | Şu anda tüketilen kredi sayısını döndürür. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | Şu anda tüketilen megabayt sayısını döndürür. |

### Örnekler

Bu örnekte, ölçümlü genel ve özel anahtarları ayarlamaya yönelik bir girişim yapılır:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
