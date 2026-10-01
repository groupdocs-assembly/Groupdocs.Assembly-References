---
title: "JsonDataLoadOptions"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Αντιπροσωπεύει επιλογές για την ανάλυση δεδομένων JSON."
type: docs
weight: 220
url: /el/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

Αντιπροσωπεύει επιλογές για την ανάλυση δεδομένων JSON.

```csharp
public class JsonDataLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | Αρχικοποιεί ένα νέο στιγμιότυπο αυτής της κλάσης με προεπιλεγμένες επιλογές. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | Λαμβάνει ή ορίζει μια σημαία που υποδεικνύει εάν μια παραγόμενη πηγή δεδομένων θα περιέχει πάντα ένα αντικείμενο για ένα στοιχείο ρίζας JSON. Εάν ένα στοιχείο ρίζας JSON περιέχει μια μόνο σύνθετη ιδιότητα, ένα τέτοιο αντικείμενο δεν δημιουργείται εξ ορισμού. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | Λαμβάνει ή ορίζει ακριβείς μορφές για την ανάλυση τιμών ημερομηνίας-ώρας JSON κατά τη φόρτωση του JSON. Η προεπιλογή είναι **null**. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | Λαμβάνει ή ορίζει μια λειτουργία για την ανάλυση απλών τιμών JSON (null, boolean, number, integer και string) κατά τη φόρτωση του JSON. Μια τέτοια λειτουργία δεν επηρεάζει την ανάλυση τιμών ημερομηνίας-ώρας. Η προεπιλογή είναι Loose. |

### Παρατηρήσεις

Ένα στιγμιότυπο αυτής της κλάσης μπορεί να περαστεί στους κατασκευαστές του [`JsonDataSource`](../jsondatasource).

### Δείτε επίσης

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
