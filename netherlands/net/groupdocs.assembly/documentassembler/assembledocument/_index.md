---
title: AssembleDocument
second_title: GroupDocs.Assembly voor .NET API-referentie
description: Laadt een sjabloondocument uit het opgegeven bronpad vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen en slaat het resultaatdocument op in het doelpad met behulp van default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /nl/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Laadt een sjabloondocument uit het opgegeven bronpad, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen en slaat het resultaatdocument op in het doelpad met behulp van default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Het pad naar een sjabloondocument dat moet worden gevuld met gegevens. |
| targetPath | String | Het pad naar een resultaatdocument. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Winstwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument is gelukt. De geretourneerde vlag heeft alleen zin als een waarde is van de[`Options`](../options) eigendom omvat deInlineErrorMessages optie.

### Zie ook

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* naamruimte [GroupDocs.Assembly](../../documentassembler)
* montage [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Laadt een sjabloondocument uit het opgegeven bronpad, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen en slaat het resultaatdocument op in het doelpad met behulp van de gegeven [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Het pad naar een sjabloondocument dat moet worden gevuld met gegevens. |
| targetPath | String | Het pad naar een resultaatdocument. |
| loadSaveOptions | LoadSaveOptions | Specificeert aanvullende opties voor het laden en opslaan van documenten. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Winstwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument is gelukt. De geretourneerde vlag heeft alleen zin als een waarde is van de[`Options`](../options) eigendom omvat deInlineErrorMessages optie.

### Zie ook

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* naamruimte [GroupDocs.Assembly](../../documentassembler)
* montage [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Laadt een sjabloondocument uit de opgegeven bronstroom, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen en slaat het resultaatdocument op in de doelstroom met behulp van default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStream | Stream | De stream waaruit een sjabloondocument moet worden gelezen. |
| targetStream | Stream | De stroom om een resultaatdocument te schrijven. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Winstwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument is gelukt. De geretourneerde vlag heeft alleen zin als een waarde is van de[`Options`](../options) eigendom omvat deInlineErrorMessages optie.

### Zie ook

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* naamruimte [GroupDocs.Assembly](../../documentassembler)
* montage [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Laadt een sjabloondocument uit de opgegeven bronstroom, vult het sjabloondocument met gegevens uit de opgegeven enkele of meerdere bronnen en slaat het resultaatdocument op in de doelstroom met behulp van de gegeven [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStream | Stream | De stream waaruit een sjabloondocument moet worden gelezen. |
| targetStream | Stream | De stroom om een resultaatdocument te schrijven. |
| loadSaveOptions | LoadSaveOptions | Specificeert aanvullende opties voor het laden en opslaan van documenten. |
| dataSourceInfos | DataSourceInfo[] | Biedt informatie over te gebruiken gegevensbronobjecten. |

### Winstwaarde

Een vlag die aangeeft of het parseren van het sjabloondocument is gelukt. De geretourneerde vlag heeft alleen zin als een waarde is van de[`Options`](../options) eigendom omvat deInlineErrorMessages optie.

### Zie ook

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* naamruimte [GroupDocs.Assembly](../../documentassembler)
* montage [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
