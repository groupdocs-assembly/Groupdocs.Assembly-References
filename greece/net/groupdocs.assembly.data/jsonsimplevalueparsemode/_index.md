---
title: "JsonSimpleValueParseMode"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Καθορίζει μια λειτουργία για την ανάλυση απλών τιμών JSON (null, boolean, number, integer και string) κατά τη φόρτωση του JSON. Μια τέτοια λειτουργία δεν επηρεάζει την ανάλυση τιμών datetime."
type: docs
weight: 240
url: /el/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

Καθορίζει μια λειτουργία για την ανάλυση απλών τιμών JSON (null, boolean, number, integer και string) κατά τη φόρτωση του JSON. Αυτή η λειτουργία δεν επηρεάζει την ανάλυση τιμών ημερομηνίας-ώρας.

```csharp
public enum JsonSimpleValueParseMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Loose | `0` | Καθορίζει τη λειτουργία όπου οι τύποι των απλών τιμών JSON προσδιορίζονται κατά την ανάλυση των συμβολοσειρών τους. Για παράδειγμα, ο τύπος του 'prop' από το απόσπασμα JSON '{ prop: \"123\" }' προσδιορίζεται ως integer σε αυτή τη λειτουργία. |
| Strict | `1` | Καθορίζει τη λειτουργία όπου οι τύποι των απλών τιμών JSON προσδιορίζονται από την ίδια τη σημειογραφία JSON. Για παράδειγμα, ο τύπος του 'prop' από το απόσπασμα JSON '{ prop: \"123\" }' προσδιορίζεται ως string σε αυτή τη λειτουργία. |

### Δείτε επίσης

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
