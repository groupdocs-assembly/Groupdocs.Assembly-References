---
title: "A consumo"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce metodi per lavorare con licenze a consumo."
type: docs
weight: 90
url: /it/net/groupdocs.assembly/metered/
---
## Metered class

Fornisce metodi per lavorare con licenze a consumo.

```csharp
public class Metered
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Metered](metered)() | Crea una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | Abilita la licenza a consumo per il componente specificando le chiavi a consumo pubbliche e private appropriate. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | Restituisce il numero di crediti attualmente consumati. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | Restituisce il numero di megabyte attualmente consumati. |

### Esempi

In questo esempio, viene effettuato un tentativo di impostare le chiavi pubbliche e private a consumo:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Vedi anche

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
