---
title: "DocumentAssembler"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Παρέχει διαδικασίες για τη συμπλήρωση εγγράφων προτύπων με δεδομένα και ένα σύνολο ρυθμίσεων για τον έλεγχο αυτών των διαδικασιών."
type: docs
weight: 40
url: /el/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

Παρέχει διαδικασίες για τη συμπλήρωση εγγράφων προτύπων με δεδομένα και ένα σύνολο ρυθμίσεων για τον έλεγχο αυτών των διαδικασιών.

```csharp
public class DocumentAssembler
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DocumentAssembler](documentassembler)() | Αρχικοποιεί ένα νέο αντικείμενο αυτής της κλάσης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | Λαμβάνει ένα σύνολο ρυθμίσεων που ελέγχουν τη δημιουργία barcode κατά τη συναρμολόγηση ενός εγγράφου. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | Λαμβάνει ένα μη ταξινομημένο σύνολο (δηλαδή, μια συλλογή μοναδικών στοιχείων) που περιέχει αντικείμενα Type των οποίων τα πλήρως ή μερικώς προσδιορισμένα ονόματα μπορούν να χρησιμοποιηθούν μέσα στα πρότυπα εγγράφων που επεξεργάζεται αυτή η παράσταση του assembler για να κληθούν τα αντίστοιχα στατικά μέλη των τύπων, να πραγματοποιηθούν μετατροπές τύπων κ.λπ. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | Λαμβάνει ή ορίζει ένα σύνολο σημαιών που ελέγχουν τη συμπεριφορά αυτής της [`DocumentAssembler`](../documentassembler) παράστασης κατά τη συναρμολόγηση ενός εγγράφου. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι κλήσεις μελών προσαρμοσμένου τύπου που εκτελούνται μέσω του API ανάκλασης βελτιστοποιούνται χρησιμοποιώντας δυναμική δημιουργία κλάσεων ή όχι. Η προεπιλεγμένη τιμή είναι true. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από το καθορισμένο ροή πηγής, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μοναδική ή πολλαπλή πηγή, και αποθηκεύει το τελικό έγγραφο στην προορισμένη ροή χρησιμοποιώντας τις προεπιλεγμένες [`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από το καθορισμένο μονοπάτι πηγής, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μοναδική ή πολλαπλή πηγή, και αποθηκεύει το τελικό έγγραφο στο προορισμένο μονοπάτι χρησιμοποιώντας τις προεπιλεγμένες [`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από το καθορισμένο ροή πηγής, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μοναδική ή πολλαπλή πηγή, και αποθηκεύει το τελικό έγγραφο στην προορισμένη ροή χρησιμοποιώντας τις δοσμένες [`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | Φορτώνει ένα έγγραφο προτύπου από το καθορισμένο μονοπάτι πηγής, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μοναδική ή πολλαπλή πηγή, και αποθηκεύει το τελικό έγγραφο στο προορισμένο μονοπάτι χρησιμοποιώντας τις δοσμένες [`LoadSaveOptions`](../loadsaveoptions). |

### Δείτε επίσης

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
