---
title: DocumentAssembler
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Παρέχει ρουτίνες για τη συμπλήρωση εγγράφων προτύπων με δεδομένα και ένα σύνολο ρυθμίσεων για τον έλεγχο αυτών των ρουτινών.
type: docs
weight: 200
url: /el/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

Παρέχει ρουτίνες για τη συμπλήρωση εγγράφων προτύπων με δεδομένα και ένα σύνολο ρυθμίσεων για τον έλεγχο αυτών των ρουτινών.

```csharp
public class DocumentAssembler
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [DocumentAssembler](documentassembler)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | Λαμβάνει ένα σύνολο ρυθμίσεων που ελέγχουν τη δημιουργία γραμμωτού κώδικα κατά τη συναρμολόγηση ενός εγγράφου. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | Λαμβάνει ένα μη ταξινομημένο σύνολο (δηλαδή, μια συλλογή μοναδικών αντικειμένων) που περιέχειType αντικείμενα , τα οποία μπορούν να χρησιμοποιηθούν πλήρως ή μερικώς αναγνωρισμένα ονόματα σε πρότυπα εγγράφων που υποβάλλονται σε επεξεργασία από αυτό το στιγμιότυπο assembler για την κλήση των στατικών μελών των αντίστοιχων τύπων, την εκτέλεση εκπομπών τύπων κ.λπ. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | Λαμβάνει ή ορίζει ένα σύνολο σημαιών που ελέγχουν τη συμπεριφορά αυτού[`DocumentAssembler`](../documentassembler) παράδειγμα κατά τη συναρμολόγηση ενός εγγράφου. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι κλήσεις μελών προσαρμοσμένου τύπου που εκτελούνται μέσω API ανάκλασης είναι βελτιστοποιημένες χρησιμοποιώντας τη δημιουργία δυναμικής κλάσης ή όχι. Η προεπιλεγμένη τιμή είναι true. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη ροή προέλευσης, συμπληρώνει το έγγραφο προτύπου με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη ροή προορισμού χρησιμοποιώντας default [`LoadSaveOptions`](../loadsaveoptions) . |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη διαδρομή προέλευσης, συμπληρώνει το πρότυπο έγγραφο με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη διαδρομή προορισμού χρησιμοποιώντας default [`LoadSaveOptions`](../loadsaveoptions) . |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη ροή προέλευσης, συμπληρώνει το έγγραφο προτύπου με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη ροή προορισμού χρησιμοποιώντας το δεδομένο [`LoadSaveOptions`](../loadsaveoptions) . |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη διαδρομή προέλευσης, συμπληρώνει το πρότυπο έγγραφο με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη διαδρομή προορισμού χρησιμοποιώντας το δεδομένο [`LoadSaveOptions`](../loadsaveoptions) . |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Assembly](../../groupdocs.assembly)
* συνέλευση [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->