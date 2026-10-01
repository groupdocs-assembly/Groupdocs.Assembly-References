---
title: "DataSourceInfo"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Δημιουργεί ένα νέο στιγμιότυπο αυτής της κλάσης χωρίς να έχουν οριστεί ιδιότητες."
type: docs
weight: 10
url: /el/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

Δημιουργεί ένα νέο στιγμιότυπο αυτής της κλάσης χωρίς να έχουν οριστεί ιδιότητες.

```csharp
public DataSourceInfo()
```

### Δείτε επίσης

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

Δημιουργεί ένα νέο στιγμιότυπο αυτής της κλάσης με το καθορισμένο αντικείμενο πηγής δεδομένων.

```csharp
public DataSourceInfo(object dataSource)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataSource | Object | Το αντικείμενο προέλευσης δεδομένων. |

### Παρατηρήσεις

Το αντικείμενο προέλευσης δεδομένων μπορεί να είναι ενός από τους παρακάτω τύπους:

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

Για πληροφορίες σχετικά με το πώς να εργαστείτε με προελεύσεις δεδομένων διαφορετικών τύπων σε έγγραφα προτύπων, δείτε το template syntax reference (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Δείτε επίσης

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

Δημιουργεί ένα νέο στιγμιότυπο αυτής της κλάσης με το αντικείμενο πηγής δεδομένων και το όνομά του καθορισμένα.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataSource | Object | Το αντικείμενο προέλευσης δεδομένων. |
| name | String | Το όνομα του αντικειμένου πηγής δεδομένων που θα χρησιμοποιηθεί για πρόσβαση στο αντικείμενο πηγής δεδομένων σε ένα έγγραφο προτύπου. |

### Παρατηρήσεις

Το αντικείμενο προέλευσης δεδομένων μπορεί να είναι ενός από τους παρακάτω τύπους:

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

Για πληροφορίες σχετικά με το πώς να εργαστείτε με προελεύσεις δεδομένων διαφορετικών τύπων σε έγγραφα προτύπων, δείτε το template syntax reference (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Όταν καθορίζεται το όνομα του αντικειμένου προέλευσης δεδομένων, μπορείτε να έχετε πρόσβαση στο αντικείμενο προέλευσης δεδομένων και στα μέλη του σε ένα έγγραφο προτύπου χρησιμοποιώντας το όνομα.

Όταν το όνομα του αντικειμένου προέλευσης δεδομένων είναι null ή κενό, μπορείτε ακόμη να έχετε πρόσβαση στα μέλη του αντικειμένου προέλευσης δεδομένων σε ένα έγγραφο προτύπου χρησιμοποιώντας πρόσβαση μελών του αντικειμένου περιβάλλοντος (δείτε το Template Syntax Reference για περισσότερες πληροφορίες), αλλά δεν μπορείτε να έχετε πρόσβαση στο ίδιο το αντικείμενο προέλευσης δεδομένων.

Κατά τη μεταφορά πολλαπλών παραδειγμάτων [`DataSourceInfo`](../../datasourceinfo) στο [`DocumentAssembler`](../../documentassembler), μόνο το όνομα του πρώτου αντικειμένου προέλευσης δεδομένων μπορεί να είναι null ή κενό. Τα ονόματα των υπολοίπων πρέπει να καθορίζονται και να είναι μοναδικά.

### Δείτε επίσης

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
