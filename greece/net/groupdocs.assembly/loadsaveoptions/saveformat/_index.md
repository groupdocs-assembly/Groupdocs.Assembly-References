---
title: "SaveFormat"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει ένα μορφότυπο αρχείου για αποθήκευση ενός συναρμολογημένου εγγράφου. Η προεπιλογή είναι ακαθόριστο."
type: docs
weight: 40
url: /el/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

Λαμβάνει ή ορίζει ένα μορφότυπο αρχείου για αποθήκευση ενός συναρμολογημένου εγγράφου. Η προεπιλογή είναι ακαθόριστο.

```csharp
public FileFormat SaveFormat { get; set; }
```

### Παρατηρήσεις

Όταν η τιμή αυτής της ιδιότητας δεν καθορίζεται, το [`DocumentAssembler`](../../documentassembler) συμπεριφέρεται ως εξής:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

Προσοχή, δεν είναι πάντα δυνατό να αποθηκεύσετε ένα συναρμολογημένο έγγραφο σε οποιαδήποτε μορφή αρχείου χρησιμοποιώντας το GroupDocs.Assembly. Για παράδειγμα, είναι αδύνατο να αποθηκεύσετε ένα έγγραφο που φορτώθηκε από μορφή επεξεργασίας κειμένου (όπως DOCX) σε μορφή λογιστικού φύλλου (όπως XLSX). Για περισσότερες πληροφορίες σχετικά με τις δυνατές συνδυαστικές μορφές φόρτωσης και αποθήκευσης που υποστηρίζονται από το GroupDocs.Assembly, παρακαλούμε ελέγξτε την online τεκμηρίωση του GroupDocs.Assembly.

### Δείτε επίσης

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
