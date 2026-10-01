---
title: "DocumentTableCollection"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Αντιπροσωπεύει μια συλλογή μόνο για ανάγνωση αντικειμένων DocumentTable./documenttable ενός συγκεκριμένου αντικειμένου DocumentTableSet./documenttableset."
type: docs
weight: 130
url: /el/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Αντιπροσωπεύει μια συλλογή μόνο για ανάγνωση αντικειμένων [`DocumentTable`](../documenttable) ενός συγκεκριμένου αντικειμένου [`DocumentTableSet`](../documenttableset).

```csharp
public class DocumentTableCollection : IEnumerable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Λαμβάνει τον συνολικό αριθμό των αντικειμένων [`DocumentTable`](../documenttable) στη συλλογή. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | Λαμβάνει μια παρουσία του [`DocumentTable`](../documenttable) από τη συλλογή στον καθορισμένο δείκτη. (2 δείκτες) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η συλλογή περιέχει τον καθορισμένο πίνακα. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η συλλογή περιέχει έναν πίνακα με το καθορισμένο όνομα. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Επιστρέφει έναν απαριθμητή για την επανάληψη των αντικειμένων [`DocumentTable`](../documenttable) αυτής της συλλογής. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Επιστρέφει το δείκτη του καθορισμένου πίνακα μέσα σε αυτή τη συλλογή. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Επιστρέφει το δείκτη ενός πίνακα με το καθορισμένο όνομα μέσα σε αυτή τη συλλογή. |

### Παρατηρήσεις

Η συλλογή γεμίζει αυτόματα κατά τη φόρτωση των αντίστοιχων πινάκων από ένα έγγραφο και δεν μπορεί να τροποποιηθεί. Ωστόσο, οι ιδιότητες των αντικειμένων [`DocumentTable`](../documenttable) που περιέχονται στη συλλογή μπορούν να τροποποιηθούν.

### Δείτε επίσης

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
