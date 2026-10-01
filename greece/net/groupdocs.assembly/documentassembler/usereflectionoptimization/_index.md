---
title: "UseReflectionOptimization"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι κλήσεις μελών προσαρμοσμένου τύπου που εκτελούνται μέσω του API ανάκλασης βελτιστοποιούνται χρησιμοποιώντας δυναμική δημιουργία κλάσεων ή όχι. Η προεπιλεγμένη τιμή είναι true."
type: docs
weight: 60
url: /el/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι κλήσεις μελών προσαρμοσμένου τύπου που εκτελούνται μέσω του API ανάκλασης βελτιστοποιούνται χρησιμοποιώντας δυναμική δημιουργία κλάσεων ή όχι. Η προεπιλεγμένη τιμή είναι true.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Παρατηρήσεις

Υπάρχουν ορισμένα σενάρια όπου είναι προτιμότερο να απενεργοποιήσετε αυτή τη βελτιστοποίηση. Για παράδειγμα, εάν εργάζεστε συνεχώς με μικρές συλλογές δεδομένων, τότε το κόστος της δυναμικής δημιουργίας κλάσεων μπορεί να είναι πιο εμφανές από το κόστος των άμεσων κλήσεων του API reflection.

### Δείτε επίσης

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
