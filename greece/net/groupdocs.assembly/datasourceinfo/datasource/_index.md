---
title: "DataSource"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει το αντικείμενο πηγής δεδομένων."
type: docs
weight: 20
url: /el/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

Λαμβάνει ή ορίζει το αντικείμενο πηγής δεδομένων.

```csharp
public object DataSource { get; set; }
```

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

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
