---
title: AssembleDocument
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη διαδρομή προέλευσης συμπληρώνει το πρότυπο έγγραφο με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη διαδρομή προορισμού χρησιμοποιώντας default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /el/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη διαδρομή προέλευσης, συμπληρώνει το πρότυπο έγγραφο με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη διαδρομή προορισμού χρησιμοποιώντας default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Η διαδρομή προς ένα πρότυπο έγγραφο που θα συμπληρωθεί με δεδομένα. |
| targetPath | String | Η διαδρομή προς ένα έγγραφο αποτελεσμάτων. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες σχετικά με τα αντικείμενα προέλευσης δεδομένων που θα χρησιμοποιηθούν. |

### Επιστρεφόμενη Αξία

Μια σημαία που υποδεικνύει εάν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν μια τιμή του[`Options`](../options) ιδιοκτησία περιλαμβάνει τοInlineErrorMessages επιλογή.

### Δείτε επίσης

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* χώρος ονομάτων [GroupDocs.Assembly](../../documentassembler)
* συνέλευση [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη διαδρομή προέλευσης, συμπληρώνει το πρότυπο έγγραφο με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη διαδρομή προορισμού χρησιμοποιώντας το δεδομένο [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Η διαδρομή προς ένα πρότυπο έγγραφο που θα συμπληρωθεί με δεδομένα. |
| targetPath | String | Η διαδρομή προς ένα έγγραφο αποτελεσμάτων. |
| loadSaveOptions | LoadSaveOptions | Καθορίζει πρόσθετες επιλογές για τη φόρτωση και αποθήκευση εγγράφων. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες σχετικά με τα αντικείμενα προέλευσης δεδομένων που θα χρησιμοποιηθούν. |

### Επιστρεφόμενη Αξία

Μια σημαία που υποδεικνύει εάν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν μια τιμή του[`Options`](../options) ιδιοκτησία περιλαμβάνει τοInlineErrorMessages επιλογή.

### Δείτε επίσης

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* χώρος ονομάτων [GroupDocs.Assembly](../../documentassembler)
* συνέλευση [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη ροή προέλευσης, συμπληρώνει το έγγραφο προτύπου με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη ροή προορισμού χρησιμοποιώντας default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStream | Stream | Η ροή για την ανάγνωση ενός εγγράφου προτύπου. |
| targetStream | Stream | Η ροή για τη σύνταξη ενός εγγράφου αποτελέσματος. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες σχετικά με τα αντικείμενα προέλευσης δεδομένων που θα χρησιμοποιηθούν. |

### Επιστρεφόμενη Αξία

Μια σημαία που υποδεικνύει εάν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν μια τιμή του[`Options`](../options) ιδιοκτησία περιλαμβάνει τοInlineErrorMessages επιλογή.

### Δείτε επίσης

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* χώρος ονομάτων [GroupDocs.Assembly](../../documentassembler)
* συνέλευση [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Φορτώνει ένα έγγραφο προτύπου από την καθορισμένη ροή προέλευσης, συμπληρώνει το έγγραφο προτύπου με δεδομένα από τις καθορισμένες μεμονωμένες ή πολλαπλές πηγές και αποθηκεύει το έγγραφο αποτελέσματος στη ροή προορισμού χρησιμοποιώντας το δεδομένο [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStream | Stream | Η ροή για την ανάγνωση ενός εγγράφου προτύπου. |
| targetStream | Stream | Η ροή για τη σύνταξη ενός εγγράφου αποτελέσματος. |
| loadSaveOptions | LoadSaveOptions | Καθορίζει πρόσθετες επιλογές για τη φόρτωση και αποθήκευση εγγράφων. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες σχετικά με τα αντικείμενα προέλευσης δεδομένων που θα χρησιμοποιηθούν. |

### Επιστρεφόμενη Αξία

Μια σημαία που υποδεικνύει εάν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν μια τιμή του[`Options`](../options) ιδιοκτησία περιλαμβάνει τοInlineErrorMessages επιλογή.

### Δείτε επίσης

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* χώρος ονομάτων [GroupDocs.Assembly](../../documentassembler)
* συνέλευση [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
