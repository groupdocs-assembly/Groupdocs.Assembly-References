---
title: "Abgerechnet"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Methoden zur Arbeit mit nutzungsbasierten Lizenzen bereit."
type: docs
weight: 90
url: /de/net/groupdocs.assembly/metered/
---
## Metered class

Stellt Methoden zur Arbeit mit nutzungsbasierten Lizenzen bereit.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered)() | Erstellt eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | Aktiviert die abgerechnete Lizenzierung für die Komponente, indem geeignete öffentliche und private Metered-Schlüssel angegeben werden. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | Gibt die derzeit verbrauchte Anzahl an Credits zurück. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | Gibt die derzeit verbrauchte Menge an Megabytes zurück. |

### Beispiele

In diesem Beispiel wird versucht, abgerechnete öffentliche und private Schlüssel festzulegen:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Siehe auch

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
