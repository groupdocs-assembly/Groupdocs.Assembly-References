---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly voor .NET API-referentie"
description: "Laadt een sjabloondocument vanaf het opgegeven bronpad, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen en slaat het resulterende document op naar het doelpad met behulp van de standaard LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /nl/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Laadt een sjabloondocument vanaf het opgegeven bronpad, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen, en slaat het resulterende document op naar het doelpad met behulp van de standaard [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Het pad naar een sjabloondocument dat met gegevens moet worden gevuld. |
| targetPath | String | Het pad naar een resulterend document. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Retourwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument succesvol was. De geretourneerde vlag is alleen zinvol als een waarde van de eigenschap [`Options`](../options) de optie InlineErrorMessages bevat.

### Zie ook

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Laadt een sjabloondocument vanaf het opgegeven bronpad, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen, en slaat het resulterende document op naar het doelpad met behulp van de opgegeven [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Het pad naar een sjabloondocument dat met gegevens moet worden gevuld. |
| targetPath | String | Het pad naar een resulterend document. |
| loadSaveOptions | LoadSaveOptions | Specificeert extra opties voor het laden en opslaan van documenten. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Retourwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument succesvol was. De geretourneerde vlag is alleen zinvol als een waarde van de eigenschap [`Options`](../options) de optie InlineErrorMessages bevat.

### Zie ook

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Laadt een sjabloondocument vanaf de opgegeven bronstroom, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen, en slaat het resulterende document op naar de doelstroom met behulp van de standaard [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStream | Stream | De stroom om een sjabloondocument uit te lezen. |
| targetStream | Stream | De stroom om een resulterend document te schrijven. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Retourwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument succesvol was. De geretourneerde vlag is alleen zinvol als een waarde van de eigenschap [`Options`](../options) de optie InlineErrorMessages bevat.

### Zie ook

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Laadt een sjabloondocument vanaf de opgegeven bronstroom, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen, en slaat het resulterende document op naar de doelstroom met behulp van de opgegeven [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStream | Stream | De stroom om een sjabloondocument uit te lezen. |
| targetStream | Stream | De stroom om een resulterend document te schrijven. |
| loadSaveOptions | LoadSaveOptions | Specificeert extra opties voor het laden en opslaan van documenten. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Retourwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument succesvol was. De geretourneerde vlag is alleen zinvol als een waarde van de eigenschap [`Options`](../options) de optie InlineErrorMessages bevat.

### Zie ook

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
