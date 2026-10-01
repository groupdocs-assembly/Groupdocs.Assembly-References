---
title: "DataSourceInfo"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Erstellt eine neue Instanz dieser Klasse, ohne dass Eigenschaften angegeben werden."
type: docs
weight: 10
url: /de/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

Erstellt eine neue Instanz dieser Klasse, ohne dass Eigenschaften angegeben werden.

```csharp
public DataSourceInfo()
```

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

Erstellt eine neue Instanz dieser Klasse mit dem angegebenen Datenquellenobjekt.

```csharp
public DataSourceInfo(object dataSource)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataSource | Objekt | Das Datenquellenobjekt. |

### Hinweise

Das Datenquellenobjekt kann einer der folgenden Typen sein:

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

Weitere Informationen darüber, wie man mit Datenquellen verschiedener Typen in Vorlagendokumenten arbeitet, finden Sie in der Referenz zur Vorlagensyntax (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

Erstellt eine neue Instanz dieser Klasse mit dem Datenquellenobjekt und dessen Namen.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataSource | Objekt | Das Datenquellenobjekt. |
| name | String | Der Name des Datenquellenobjekts, das verwendet wird, um auf das Datenquellenobjekt in einem Vorlagendokument zuzugreifen. |

### Hinweise

Das Datenquellenobjekt kann einer der folgenden Typen sein:

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

Weitere Informationen darüber, wie man mit Datenquellen verschiedener Typen in Vorlagendokumenten arbeitet, finden Sie in der Referenz zur Vorlagensyntax (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Wenn der Name des Datenquellen‑Objekts angegeben ist, können Sie auf das Datenquellen‑Objekt und seine Mitglieder in einem Vorlagendokument über den Namen zugreifen.

Wenn der Name des Datenquellen‑Objekts null oder leer ist, können Sie weiterhin über den Kontext‑Objekt‑Member‑Zugriff (siehe Template‑Syntax‑Referenz für weitere Informationen) auf die Mitglieder des Datenquellen‑Objekts in einem Vorlagendokument zugreifen, jedoch nicht auf das Datenquellen‑Objekt selbst.

Beim Übergeben mehrerer [`DataSourceInfo`](../../datasourceinfo)-Instanzen an [`DocumentAssembler`](../../documentassembler) darf nur der Name des ersten Datenquellen‑Objekts null oder leer sein. Die Namen der übrigen Objekte müssen angegeben und eindeutig sein.

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
