---
title: AssembleDocument
second_title: GroupDocs.Assembly för .NET API-referens
description: Laddar ett malldokument från den angivna källsökvägen fyller malldokumentet med data från de angivna enstaka eller flera källorna och lagrar resultatdokumentet till målsökvägen med standard LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /sv/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Laddar ett malldokument från den angivna källsökvägen, fyller malldokumentet med data från de angivna enstaka eller flera källorna och lagrar resultatdokumentet till målsökvägen med standard [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sökvägen till ett malldokument som ska fyllas i med data. |
| targetPath | String | Sökvägen till ett resultatdokument. |
| dataSourceInfos | DataSourceInfo[] | Ger information om datakällans objekt som ska användas. |

### Returvärde

En flagga som indikerar om analysen av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde av[`Options`](../options) egendom omfattarInlineErrorMessages option.

### Se även

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namnutrymme [GroupDocs.Assembly](../../documentassembler)
* hopsättning [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Laddar ett malldokument från den angivna källsökvägen, fyller malldokumentet med data från de angivna enstaka eller flera källorna och lagrar resultatdokumentet till målsökvägen med hjälp av given [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sökvägen till ett malldokument som ska fyllas i med data. |
| targetPath | String | Sökvägen till ett resultatdokument. |
| loadSaveOptions | LoadSaveOptions | Anger ytterligare alternativ för att ladda och spara dokument. |
| dataSourceInfos | DataSourceInfo[] | Ger information om datakällans objekt som ska användas. |

### Returvärde

En flagga som indikerar om analysen av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde av[`Options`](../options) egendom omfattarInlineErrorMessages option.

### Se även

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namnutrymme [GroupDocs.Assembly](../../documentassembler)
* hopsättning [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Laddar ett malldokument från den angivna källströmmen, fyller malldokumentet med data från de angivna enstaka eller flera källorna och lagrar resultatdokumentet i målströmmen med standard [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStream | Stream | Streamen att läsa ett malldokument från. |
| targetStream | Stream | Strömmen för att skriva ett resultatdokument. |
| dataSourceInfos | DataSourceInfo[] | Ger information om datakällans objekt som ska användas. |

### Returvärde

En flagga som indikerar om analysen av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde av[`Options`](../options) egendom omfattarInlineErrorMessages option.

### Se även

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namnutrymme [GroupDocs.Assembly](../../documentassembler)
* hopsättning [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Laddar ett malldokument från den angivna källströmmen, fyller malldokumentet med data från de angivna enstaka eller flera källorna och lagrar resultatdokumentet i målflödet med hjälp av given [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStream | Stream | Streamen att läsa ett malldokument från. |
| targetStream | Stream | Strömmen för att skriva ett resultatdokument. |
| loadSaveOptions | LoadSaveOptions | Anger ytterligare alternativ för att ladda och spara dokument. |
| dataSourceInfos | DataSourceInfo[] | Ger information om datakällans objekt som ska användas. |

### Returvärde

En flagga som indikerar om analysen av malldokumentet lyckades. Den returnerade flaggan är bara meningsfull om ett värde av[`Options`](../options) egendom omfattarInlineErrorMessages option.

### Se även

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namnutrymme [GroupDocs.Assembly](../../documentassembler)
* hopsättning [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
