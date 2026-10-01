---
title: "ExactDateTimeParseFormats"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει ακριβείς μορφές για την ανάλυση τιμών datetime JSON κατά τη φόρτωση του JSON. Η προεπιλογή είναι null."
type: docs
weight: 30
url: /el/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

Λαμβάνει ή ορίζει ακριβείς μορφές για την ανάλυση τιμών ημερομηνίας-ώρας JSON κατά τη φόρτωση του JSON. Η προεπιλογή είναι **null**.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Παρατηρήσεις

Οι συμβολοσειρές που κωδικοποιούνται χρησιμοποιώντας τη μορφή ημερομηνίας-ώρας Microsoft® JSON (για παράδειγμα, "/Date(1224043200000)/") αναγνωρίζονται πάντα ως τιμές ημερομηνίας-ώρας ανεξάρτητα από την τιμή αυτής της ιδιότητας. Η ιδιότητα ορίζει πρόσθετες μορφές που θα χρησιμοποιηθούν κατά την ανάλυση τιμών ημερομηνίας-ώρας από συμβολοσειρές με τον ακόλουθο τρόπο:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### Δείτε επίσης

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
