---
title: "Name"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder setzt den Namen des Datenquellenobjekts, das zum Zugriff auf das Datenquellenobjekt in einem Vorlagendokument verwendet wird."
type: docs
weight: 30
url: /de/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

Liest oder setzt den Namen des Datenquellenobjekts, das zum Zugriff auf das Datenquellenobjekt in einem Vorlagendokument verwendet wird.

```csharp
public string Name { get; set; }
```

### Hinweise

Wenn der Name des Datenquellen‑Objekts angegeben ist, können Sie auf das Datenquellen‑Objekt und seine Mitglieder in einem Vorlagendokument über den Namen zugreifen.

Wenn der Name des Datenquellen‑Objekts null oder leer ist, können Sie weiterhin über den Kontext‑Objekt‑Member‑Zugriff (siehe Template‑Syntax‑Referenz für weitere Informationen) auf die Mitglieder des Datenquellen‑Objekts in einem Vorlagendokument zugreifen, jedoch nicht auf das Datenquellen‑Objekt selbst.

Beim Übergeben mehrerer [`DataSourceInfo`](../../datasourceinfo)-Instanzen an [`DocumentAssembler`](../../documentassembler) darf nur der Name des ersten Datenquellen‑Objekts null oder leer sein. Die Namen der übrigen Objekte müssen angegeben und eindeutig sein.

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
