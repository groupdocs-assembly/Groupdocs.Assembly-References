---
title: "BarcodeSettings"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Αντιπροσωπεύει ένα σύνολο ρυθμίσεων που ελέγχουν τη δημιουργία barcode κατά τη συναρμολόγηση ενός εγγράφου."
type: docs
weight: 10
url: /el/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

Αντιπροσωπεύει ένα σύνολο ρυθμίσεων που ελέγχουν τη δημιουργία barcode κατά τη συναρμολόγηση ενός εγγράφου.

```csharp
public class BarcodeSettings
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | Λαμβάνει ή ορίζει μια βασική διάσταση x, δηλαδή το μικρότερο πλάτος της μονάδας των γραμμών και κενών του barcode. Μετράται σε [`GraphicsUnit`](./graphicsunit). |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | Λαμβάνει ή ορίζει μια βασική διάσταση y, δηλαδή το μικρότερο ύψος της μονάδας των 2Δ modules του barcode. Μετράται σε [`GraphicsUnit`](./graphicsunit). |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | Λαμβάνει ή ορίζει μια μονάδα γραφικών που χρησιμοποιείται για τη μέτρηση των [`BaseXDimension`](./basexdimension) και [`BaseYDimension`](./baseydimension). Η προεπιλεγμένη τιμή είναι Millimeter. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια και κάθετη ανάλυση μιας εικόνας barcode που δημιουργείται. Μετράται σε κουκκίδες ανά ίντσα. Η προεπιλεγμένη τιμή είναι 96. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν μια μη έγκυρη τιμή barcode πρέπει να διορθωθεί αυτόματα (εάν είναι δυνατόν) ώστε να ταιριάζει με τις προδιαγραφές του barcode ή εάν πρέπει να εξαχθεί εξαίρεση για να υποδείξει το σφάλμα. Η προεπιλεγμένη τιμή είναι true. |

### Δείτε επίσης

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
