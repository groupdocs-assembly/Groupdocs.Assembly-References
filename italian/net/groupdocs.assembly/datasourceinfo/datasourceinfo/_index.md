---
title: "DataSourceInfo"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Crea una nuova istanza di questa classe senza specificare alcuna proprietà."
type: docs
weight: 10
url: /it/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

Crea una nuova istanza di questa classe senza specificare alcuna proprietà.

```csharp
public DataSourceInfo()
```

### Vedi anche

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

Crea una nuova istanza di questa classe con l'oggetto data source specificato.

```csharp
public DataSourceInfo(object dataSource)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataSource | Object | L'oggetto data source. |

### Osservazioni

L'oggetto data source può essere di uno dei seguenti tipi:

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

Per informazioni su come lavorare con data source di diversi tipi nei documenti modello, vedere il riferimento alla sintassi del modello (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Vedi anche

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

Crea una nuova istanza di questa classe con l'oggetto data source e il suo nome specificati.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataSource | Object | L'oggetto data source. |
| name | String | Il nome dell'oggetto origine dati da utilizzare per accedere all'oggetto origine dati in un documento modello. |

### Osservazioni

L'oggetto data source può essere di uno dei seguenti tipi:

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

Per informazioni su come lavorare con data source di diversi tipi nei documenti modello, vedere il riferimento alla sintassi del modello (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Quando il nome dell'oggetto data source è specificato, è possibile accedere all'oggetto data source e ai suoi membri in un documento modello utilizzando il nome.

Quando il nome dell'oggetto data source è null o vuoto, è comunque possibile accedere ai membri dell'oggetto data source in un documento modello utilizzando l'accesso ai membri dell'oggetto contesto (vedi Riferimento alla sintassi del modello per ulteriori informazioni), ma non è possibile accedere all'oggetto data source stesso.

Quando si passano più istanze di [`DataSourceInfo`](../../datasourceinfo) a [`DocumentAssembler`](../../documentassembler), solo il nome del primo oggetto data source può essere null o vuoto. I nomi degli altri devono essere specificati e unici.

### Vedi anche

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
