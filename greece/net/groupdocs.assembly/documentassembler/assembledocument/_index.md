---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Φορτώνει ένα έγγραφο προτύπου από τη συγκεκριμένη διαδρομή προέλευσης, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μία ή πολλές πηγές και αποθηκεύει το τελικό έγγραφο στη διαδρομή προορισμού χρησιμοποιώντας τις προεπιλεγμένες LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /el/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Φορτώνει ένα έγγραφο προτύπου από τη συγκεκριμένη διαδρομή προέλευσης, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μία ή πολλές πηγές και αποθηκεύει το τελικό έγγραφο στη διαδρομή προορισμού χρησιμοποιώντας τις προεπιλεγμένες [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Η διαδρομή προς ένα έγγραφο προτύπου που θα γεμίσει με δεδομένα. |
| targetPath | String | Η διαδρομή προς το τελικό έγγραφο. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες για τα αντικείμενα πηγής δεδομένων που θα χρησιμοποιηθούν. |

### Τιμή Επιστροφής

Μία σημαία που υποδεικνύει αν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν η τιμή της ιδιότητας [`Options`](../options) περιλαμβάνει την επιλογή InlineErrorMessages.

### Δείτε επίσης

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Φορτώνει ένα έγγραφο προτύπου από τη συγκεκριμένη διαδρομή προέλευσης, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μία ή πολλές πηγές και αποθηκεύει το τελικό έγγραφο στη διαδρομή προορισμού χρησιμοποιώντας τις δοθείσες [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Η διαδρομή προς ένα έγγραφο προτύπου που θα γεμίσει με δεδομένα. |
| targetPath | String | Η διαδρομή προς το τελικό έγγραφο. |
| loadSaveOptions | LoadSaveOptions | Καθορίζει πρόσθετες επιλογές για τη φόρτωση και αποθήκευση εγγράφων. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες για τα αντικείμενα πηγής δεδομένων που θα χρησιμοποιηθούν. |

### Τιμή Επιστροφής

Μία σημαία που υποδεικνύει αν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν η τιμή της ιδιότητας [`Options`](../options) περιλαμβάνει την επιλογή InlineErrorMessages.

### Δείτε επίσης

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Φορτώνει ένα έγγραφο προτύπου από το καθορισμένο ρεύμα προέλευσης, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μία ή πολλές πηγές και αποθηκεύει το τελικό έγγραφο στο ρεύμα προορισμού χρησιμοποιώντας τις προεπιλεγμένες [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStream | Stream | Το ρεύμα από το οποίο θα διαβαστεί ένα έγγραφο προτύπου. |
| targetStream | Stream | Το ρεύμα στο οποίο θα γραφτεί το τελικό έγγραφο. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες για τα αντικείμενα πηγής δεδομένων που θα χρησιμοποιηθούν. |

### Τιμή Επιστροφής

Μία σημαία που υποδεικνύει αν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν η τιμή της ιδιότητας [`Options`](../options) περιλαμβάνει την επιλογή InlineErrorMessages.

### Δείτε επίσης

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Φορτώνει ένα έγγραφο προτύπου από το καθορισμένο ρεύμα προέλευσης, γεμίζει το έγγραφο προτύπου με δεδομένα από την καθορισμένη μία ή πολλές πηγές και αποθηκεύει το τελικό έγγραφο στο ρεύμα προορισμού χρησιμοποιώντας τις δοθείσες [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStream | Stream | Το ρεύμα από το οποίο θα διαβαστεί ένα έγγραφο προτύπου. |
| targetStream | Stream | Το ρεύμα στο οποίο θα γραφτεί το τελικό έγγραφο. |
| loadSaveOptions | LoadSaveOptions | Καθορίζει πρόσθετες επιλογές για τη φόρτωση και αποθήκευση εγγράφων. |
| dataSourceInfos | DataSourceInfo[] | Παρέχει πληροφορίες για τα αντικείμενα πηγής δεδομένων που θα χρησιμοποιηθούν. |

### Τιμή Επιστροφής

Μία σημαία που υποδεικνύει αν η ανάλυση του εγγράφου προτύπου ήταν επιτυχής. Η επιστρεφόμενη σημαία έχει νόημα μόνο εάν η τιμή της ιδιότητας [`Options`](../options) περιλαμβάνει την επιλογή InlineErrorMessages.

### Δείτε επίσης

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
