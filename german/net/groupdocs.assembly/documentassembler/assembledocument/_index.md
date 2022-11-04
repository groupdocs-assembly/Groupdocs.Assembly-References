---
title: AssembleDocument
second_title: GroupDocs.Assembly für .NET-API-Referenz
description: Lädt ein Vorlagendokument aus dem angegebenen Quellpfad füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument unter Verwendung von default im Zielpfad.LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /de/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Lädt ein Vorlagendokument aus dem angegebenen Quellpfad, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument unter Verwendung von default im Zielpfad.[`LoadSaveOptions`](../../loadsaveoptions) .

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

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag macht nur Sinn, wenn ein Wert von ist[`Options`](../options) Eigentum umfasst dieInlineErrorMessages Option.

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namensraum [GroupDocs.Assembly](../../documentassembler)
* Montage [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Lädt ein Vorlagendokument aus dem angegebenen Quellpfad, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument unter Verwendung des angegebenen im Zielpfad.[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Der Pfad zu einem Vorlagendokument, das mit Daten gefüllt werden soll. |
| targetPath | String | Der Pfad zu einem Ergebnisdokument. |
| loadSaveOptions | LoadSaveOptions | Gibt zusätzliche Optionen zum Laden und Speichern von Dokumenten an. |
| dataSourceInfos | DataSourceInfo[] | Stellt Informationen zu zu verwendenden Datenquellenobjekten bereit. |

### Rückgabewert

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag macht nur Sinn, wenn ein Wert von ist[`Options`](../options) Eigentum umfasst dieInlineErrorMessages Option.

### Siehe auch

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namensraum [GroupDocs.Assembly](../../documentassembler)
* Montage [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Lädt ein Vorlagendokument aus dem angegebenen Quellstream, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument im Zielstream unter Verwendung von default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStream | Stream | Der Stream, aus dem ein Vorlagendokument gelesen werden soll. |
| targetStream | Stream | Der Stream zum Schreiben eines Ergebnisdokuments. |
| dataSourceInfos | DataSourceInfo[] | Stellt Informationen zu zu verwendenden Datenquellenobjekten bereit. |

### Rückgabewert

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag macht nur Sinn, wenn ein Wert von ist[`Options`](../options) Eigentum umfasst dieInlineErrorMessages Option.

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namensraum [GroupDocs.Assembly](../../documentassembler)
* Montage [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Lädt ein Vorlagendokument aus dem angegebenen Quellstream, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument im Zielstream unter Verwendung des angegebenen [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStream | Stream | Der Stream, aus dem ein Vorlagendokument gelesen werden soll. |
| targetStream | Stream | Der Stream zum Schreiben eines Ergebnisdokuments. |
| loadSaveOptions | LoadSaveOptions | Gibt zusätzliche Optionen zum Laden und Speichern von Dokumenten an. |
| dataSourceInfos | DataSourceInfo[] | Stellt Informationen zu zu verwendenden Datenquellenobjekten bereit. |

### Rückgabewert

Ein Flag, das angibt, ob das Parsen des Vorlagendokuments erfolgreich war. Das zurückgegebene Flag macht nur Sinn, wenn ein Wert von ist[`Options`](../options) Eigentum umfasst dieInlineErrorMessages Option.

### Siehe auch

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namensraum [GroupDocs.Assembly](../../documentassembler)
* Montage [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
