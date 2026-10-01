---
title: "Μετρημένο"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Παρέχει μεθόδους για εργασία με αδειοδότηση με μέτρηση."
type: docs
weight: 90
url: /el/net/groupdocs.assembly/metered/
---
## Metered class

Παρέχει μεθόδους για εργασία με αδειοδότηση με μέτρηση.

```csharp
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered)() | Δημιουργεί ένα νέο αντίγραφο αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | Ενεργοποιεί τη μετρημένη άδεια για το στοιχείο, καθορίζοντας τα κατάλληλα δημόσια και ιδιωτικά κλειδιά μέτρησης. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | Επιστρέφει τον τρέχοντα αριθμό καταναλωμένων πόντων. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | Επιστρέφει τον τρέχοντα αριθμό καταναλωμένων megabytes. |

### Παραδείγματα

Σε αυτό το παράδειγμα, γίνεται προσπάθεια να οριστούν τα δημόσια και ιδιωτικά κλειδιά μέτρησης:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Δείτε επίσης

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
