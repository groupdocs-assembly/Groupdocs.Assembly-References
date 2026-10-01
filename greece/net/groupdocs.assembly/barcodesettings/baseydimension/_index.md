---
title: "BaseYDimension"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει μια βασική διάσταση y που είναι το μικρότερο ύψος της μονάδας των 2D modules του barcode. Μετράται σε GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit."
type: docs
weight: 20
url: /el/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

Λαμβάνει ή ορίζει μια βασική διάσταση y, δηλαδή το μικρότερο ύψος της μονάδας των 2D modules του barcode. Μετράται σε [`GraphicsUnit`](../graphicsunit).

```csharp
public float BaseYDimension { get; set; }
```

### Παρατηρήσεις

Τα barcode ορισμένων τύπων (όπως data matrix) μπορεί να αγνοούν τη διάσταση y και να χρησιμοποιούν τη διάσταση x και για τις μονάδες πλάτους και ύψους.

Όταν εφαρμόζεται κλιμάκωση barcode μέσω προτύπου, μια πραγματική διάσταση y υπολογίζεται με βάση τη βασική διάσταση y και έναν συντελεστή κλιμάκωσης.

### Δείτε επίσης

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
