---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Lädt ein Vorlagendokument vom angegebenen Quellpfad, füllt das Vorlagendokument mit Daten aus der angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument am Zielpfad unter Verwendung der Standard‑LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /de/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Lädt ein Vorlagendokument vom angegebenen Quellpfad, füllt das Vorlagendokument mit Daten aus der angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument am Zielpfad unter Verwendung der Standard‑[`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Der Pfad zu einem Vorlagendokument, das mit Daten gefüllt werden soll. |
| targetPath | String | Der Pfad zu einem Ergebnisdokument. |
| dataSourceInfos | DataSourceInfo[] | Stellt Informationen zu zu verwendenden Datenquellenobjekten bereit. |

### Rückgabewert

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag ist nur sinnvoll, wenn ein Wert der [`Options`](../options)-Eigenschaft die Option InlineErrorMessages enthält.

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Lädt ein Vorlagendokument vom angegebenen Quellpfad, füllt das Vorlagendokument mit Daten aus der angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument am Zielpfad unter Verwendung der angegebenen [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Der Pfad zu einem Vorlagendokument, das mit Daten gefüllt werden soll. |
| targetPath | String | Der Pfad zu einem Ergebnisdokument. |
| loadSaveOptions | LoadSaveOptions | Gibt zusätzliche Optionen für das Laden und Speichern von Dokumenten an. |
| dataSourceInfos | DataSourceInfo[] | Stellt Informationen zu zu verwendenden Datenquellenobjekten bereit. |

### Rückgabewert

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag ist nur sinnvoll, wenn ein Wert der [`Options`](../options)-Eigenschaft die Option InlineErrorMessages enthält.

### Siehe auch

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Lädt ein Vorlagendokument aus dem angegebenen Quell‑Stream, füllt das Vorlagendokument mit Daten aus der angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument in den Ziel‑Stream unter Verwendung der Standard‑[`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStream | Stream | Der Stream, aus dem ein Vorlagendokument gelesen wird. |
| targetStream | Stream | Der Stream, in den ein Ergebnisdokument geschrieben wird. |
| dataSourceInfos | DataSourceInfo[] | Stellt Informationen zu zu verwendenden Datenquellenobjekten bereit. |

### Rückgabewert

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag ist nur sinnvoll, wenn ein Wert der [`Options`](../options)-Eigenschaft die Option InlineErrorMessages enthält.

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Lädt ein Vorlagendokument aus dem angegebenen Quell‑Stream, füllt das Vorlagendokument mit Daten aus der angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument in den Ziel‑Stream unter Verwendung der angegebenen [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStream | Stream | Der Stream, aus dem ein Vorlagendokument gelesen wird. |
| targetStream | Stream | Der Stream, in den ein Ergebnisdokument geschrieben wird. |
| loadSaveOptions | LoadSaveOptions | Gibt zusätzliche Optionen für das Laden und Speichern von Dokumenten an. |
| dataSourceInfos | DataSourceInfo[] | Stellt Informationen zu zu verwendenden Datenquellenobjekten bereit. |

### Rückgabewert

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag ist nur sinnvoll, wenn ein Wert der [`Options`](../options)-Eigenschaft die Option InlineErrorMessages enthält.

### Siehe auch

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
