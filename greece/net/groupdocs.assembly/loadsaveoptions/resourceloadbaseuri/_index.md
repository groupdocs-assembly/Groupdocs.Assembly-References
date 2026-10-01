---
title: "ResourceLoadBaseUri"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει μια βασική URI για την επίλυση εξωτερικών αρχείων πόρων από σχετικές URI σε απόλυτες κατά τη φόρτωση ενός προτύπου HTML εγγράφου που θα συναρμολογηθεί και θα αποθηκευτεί σε μορφή μη HTML. Η προεπιλεγμένη τιμή είναι μια κενή συμβολοσειρά."
type: docs
weight: 20
url: /el/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

Λαμβάνει ή ορίζει μια βασική URI για την επίλυση των σχετικών URI των εξωτερικών αρχείων πόρων σε απόλυτες, κατά τη φόρτωση ενός προτύπου HTML εγγράφου που θα συναρμολογηθεί και αποθηκευτεί σε μορφότυπο μη-HTML. Η προεπιλεγμένη τιμή είναι μια κενή συμβολοσειρά.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### Παρατηρήσεις

Κατά τη φόρτωση ενός HTML εγγράφου από αρχείο, ο φάκελος που το περιέχει χρησιμοποιείται ως βασική URI από προεπιλογή, κάτι που δεν μπορεί να συμβεί όταν το HTML έγγραφο φορτώνεται από ρεύμα. Ορίστε αυτήν την ιδιότητα για να καθορίσετε μια βασική URI κατά τη φόρτωση ενός HTML εγγράφου από ρεύμα ή για να παρακάμψετε την προεπιλεγμένη βασική URI όταν το HTML έγγραφο φορτώνεται από αρχείο.

Μια τιμή αυτής της ιδιότητας αγνοείται στις ακόλουθες περιπτώσεις:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### Δείτε επίσης

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
