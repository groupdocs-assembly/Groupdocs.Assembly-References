---
title: "Mesuré"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit des méthodes pour travailler avec la licence à comptage."
type: docs
weight: 90
url: /fr/net/groupdocs.assembly/metered/
---
## Metered class

Fournit des méthodes pour travailler avec la licence à comptage.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered)() | Crée une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | Active la licence mesurée pour le composant en spécifiant les clés publiques et privées appropriées. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | Renvoie le nombre de crédits actuellement consommés. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | Renvoie le nombre de mégaoctets actuellement consommés. |

### Exemples

Dans cet exemple, une tentative de définition des clés publiques et privées mesurées est effectuée :

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Voir aussi

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
