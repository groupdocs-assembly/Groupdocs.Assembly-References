---
title: AssembleDocument
second_title: Référence de l'API GroupDocs.Assembly pour .NET
description: Charge un modèle de document à partir du chemin source spécifié remplit le modèle de document avec des données provenant des sources uniques ou multiples spécifiées et stocke le document de résultat dans le chemin cible à laide de default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /fr/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Charge un modèle de document à partir du chemin source spécifié, remplit le modèle de document avec des données provenant des sources uniques ou multiples spécifiées et stocke le document de résultat dans le chemin cible à l'aide de default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourcePath | String | Chemin d'accès à un modèle de document à remplir avec des données. |
| targetPath | String | Chemin d'accès à un document de résultat. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets de source de données à utiliser. |

### Return_Value

Un indicateur indiquant si l'analyse du modèle de document a réussi. Le drapeau renvoyé n'a de sens que si une valeur de[`Options`](../options) la propriété comprend leInlineErrorMessages option.

### Voir également

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espace de noms [GroupDocs.Assembly](../../documentassembler)
* Assemblée [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Charge un modèle de document à partir du chemin source spécifié, remplit le modèle de document avec des données provenant de les sources uniques ou multiples spécifiées et stocke le document de résultat dans le chemin cible à l'aide de given [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourcePath | String | Chemin d'accès à un modèle de document à remplir avec des données. |
| targetPath | String | Chemin d'accès à un document de résultat. |
| loadSaveOptions | LoadSaveOptions | Spécifie des options supplémentaires pour le chargement et l'enregistrement des documents. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets de source de données à utiliser. |

### Return_Value

Un indicateur indiquant si l'analyse du modèle de document a réussi. Le drapeau renvoyé n'a de sens que si une valeur de[`Options`](../options) la propriété comprend leInlineErrorMessages option.

### Voir également

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espace de noms [GroupDocs.Assembly](../../documentassembler)
* Assemblée [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Charge un modèle de document à partir du flux source spécifié, remplit le modèle de document avec des données provenant de les sources uniques ou multiples spécifiées et stocke le document de résultat dans le flux cible à l'aide de default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourceStream | Stream | Le flux à partir duquel lire un modèle de document. |
| targetStream | Stream | Le flux pour écrire un document de résultat. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets de source de données à utiliser. |

### Return_Value

Un indicateur indiquant si l'analyse du modèle de document a réussi. Le drapeau renvoyé n'a de sens que si une valeur de[`Options`](../options) la propriété comprend leInlineErrorMessages option.

### Voir également

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espace de noms [GroupDocs.Assembly](../../documentassembler)
* Assemblée [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Charge un modèle de document à partir du flux source spécifié, remplit le modèle de document avec des données provenant de les sources uniques ou multiples spécifiées et stocke le document de résultat dans le flux cible à l'aide de given [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourceStream | Stream | Le flux à partir duquel lire un modèle de document. |
| targetStream | Stream | Le flux pour écrire un document de résultat. |
| loadSaveOptions | LoadSaveOptions | Spécifie des options supplémentaires pour le chargement et l'enregistrement des documents. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets de source de données à utiliser. |

### Return_Value

Un indicateur indiquant si l'analyse du modèle de document a réussi. Le drapeau renvoyé n'a de sens que si une valeur de[`Options`](../options) la propriété comprend leInlineErrorMessages option.

### Voir également

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espace de noms [GroupDocs.Assembly](../../documentassembler)
* Assemblée [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
