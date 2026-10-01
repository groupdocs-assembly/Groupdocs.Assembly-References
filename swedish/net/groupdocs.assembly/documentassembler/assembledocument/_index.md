---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly för .NET API-referens"
description: "Laddar ett mall‑dokument från den angivna källsökvägen, fyller mall‑dokumentet med data från de angivna enskilda eller flera källorna och sparar resultats‑dokumentet till mål‑sökvägen med standard‑LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /sv/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Laddar ett mall‑dokument från den angivna källsökvägen, fyller mall‑dokumentet med data från de angivna enskilda eller flera källorna, och sparar resultats‑dokumentet till mål‑sökvägen med standard‑[`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sökvägen till ett mall‑dokument som ska fyllas med data. |
| targetPath | String | Sökvägen till ett resultats‑dokument. |
| dataSourceInfos | DataSourceInfo[] | Tillhandahåller information om datakällobjekt som ska användas. |

### Returvärde

En flagga som indikerar om parsning av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde för egenskapen [`Options`](../options) innehåller alternativet InlineErrorMessages.

### Se även

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Laddar ett malldokument från den angivna källsökvägen, fyller malldokumentet med data från de angivna enskilda eller flera källor och sparar resultatsdokumentet till målplatsen med de angivna [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sökvägen till ett mall‑dokument som ska fyllas med data. |
| targetPath | String | Sökvägen till ett resultats‑dokument. |
| loadSaveOptions | LoadSaveOptions | Anger ytterligare alternativ för inläsning och sparande av dokument. |
| dataSourceInfos | DataSourceInfo[] | Tillhandahåller information om datakällobjekt som ska användas. |

### Returvärde

En flagga som indikerar om parsning av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde för egenskapen [`Options`](../options) innehåller alternativet InlineErrorMessages.

### Se även

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Laddar ett malldokument från den angivna källströmmen, fyller malldokumentet med data från de angivna enskilda eller flera källor och sparar resultatsdokumentet till målströmmen med standard [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStream | Stream | Strömmen att läsa ett malldokument från. |
| targetStream | Stream | Strömmen att skriva ett resultatsdokument till. |
| dataSourceInfos | DataSourceInfo[] | Tillhandahåller information om datakällobjekt som ska användas. |

### Returvärde

En flagga som indikerar om parsning av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde för egenskapen [`Options`](../options) innehåller alternativet InlineErrorMessages.

### Se även

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Laddar ett malldokument från den angivna källströmmen, fyller malldokumentet med data från de angivna enskilda eller flera källor och sparar resultatsdokumentet till målströmmen med de angivna [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStream | Stream | Strömmen att läsa ett malldokument från. |
| targetStream | Stream | Strömmen att skriva ett resultatsdokument till. |
| loadSaveOptions | LoadSaveOptions | Anger ytterligare alternativ för inläsning och sparande av dokument. |
| dataSourceInfos | DataSourceInfo[] | Tillhandahåller information om datakällobjekt som ska användas. |

### Returvärde

En flagga som indikerar om parsning av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde för egenskapen [`Options`](../options) innehåller alternativet InlineErrorMessages.

### Se även

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
