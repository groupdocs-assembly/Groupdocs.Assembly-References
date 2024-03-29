---
title: ExactDateTimeParseFormats
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Λαμβάνει ή ορίζει ακριβείς μορφές για την ανάλυση των τιμών ημερομηνίαςώρας JSON κατά τη φόρτωση του JSON. Η προεπιλογή είναιμηδενικό .
type: docs
weight: 30
url: /el/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

Λαμβάνει ή ορίζει ακριβείς μορφές για την ανάλυση των τιμών ημερομηνίας-ώρας JSON κατά τη φόρτωση του JSON. Η προεπιλογή είναι**μηδενικό** .

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Παρατηρήσεις

Οι συμβολοσειρές που κωδικοποιούνται με τη μορφή ημερομηνίας-ώρας Microsoft® JSON (για παράδειγμα, "/Date(1224043200000)/") αναγνωρίζονται πάντα ως τιμές ημερομηνίας-ώρας, ανεξάρτητα από την τιμή αυτής της ιδιότητας. Η ιδιότητα ορίζει πρόσθετες μορφές που θα χρησιμοποιηθούν κατά την ανάλυση των τιμών ημερομηνίας-ώρας από συμβολοσειρές με τον ακόλουθο τρόπο:

* Πότε`ExactDateTimeParseFormats` είναι**μηδενικό** η μορφή ISO-8601 και όλες οι μορφές ημερομηνίας-ώρας που υποστηρίζονται για τις τρέχουσες, αγγλικές ΗΠΑ και αγγλικές κουλτούρες της Νέας Ζηλανδίας χρησιμοποιούνται επιπλέον με με την αναφερόμενη σειρά.
* Πότε`ExactDateTimeParseFormats` περιέχει συμβολοσειρές, χρησιμοποιούνται ως πρόσθετες μορφές ημερομηνίας-ώρας χρησιμοποιώντας την τρέχουσα κουλτούρα.
* Πότε`ExactDateTimeParseFormats` είναι κενό, δεν χρησιμοποιούνται πρόσθετες μορφές ημερομηνίας-ώρας.

### Δείτε επίσης

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* χώρος ονομάτων [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* συνέλευση [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
