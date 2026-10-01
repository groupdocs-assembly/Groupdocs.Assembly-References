---
title: "AssembleDocument"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Charge un document modèle depuis le chemin source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées et enregistre le document résultant vers le chemin cible en utilisant les LoadSaveOptionsgroupdocs.assembly/loadsaveoptions par défaut."
type: docs
weight: 50
url: /fr/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Charge un document modèle depuis le chemin source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant vers le chemin cible en utilisant les [`LoadSaveOptions`](../../loadsaveoptions) par défaut.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Le chemin vers un document modèle à remplir avec des données. |
| targetPath | String | Le chemin vers le document résultant. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets source de données à utiliser. |

### Valeur de retour

Un indicateur indiquant si l'analyse du document modèle a réussi. L'indicateur retourné n'a de sens que si la valeur de la propriété [`Options`](../options) inclut l'option InlineErrorMessages.

### Voir aussi

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Charge un document modèle depuis le chemin source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant vers le chemin cible en utilisant les [`LoadSaveOptions`](../../loadsaveoptions) fournis.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Le chemin vers un document modèle à remplir avec des données. |
| targetPath | String | Le chemin vers le document résultant. |
| loadSaveOptions | LoadSaveOptions | Spécifie des options supplémentaires pour le chargement et l'enregistrement du document. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets source de données à utiliser. |

### Valeur de retour

Un indicateur indiquant si l'analyse du document modèle a réussi. L'indicateur retourné n'a de sens que si la valeur de la propriété [`Options`](../options) inclut l'option InlineErrorMessages.

### Voir aussi

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Charge un document modèle depuis le flux source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant vers le flux cible en utilisant les [`LoadSaveOptions`](../../loadsaveoptions) par défaut.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStream | Stream | Le flux à partir duquel lire un document modèle. |
| targetStream | Stream | Le flux dans lequel écrire le document résultant. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets source de données à utiliser. |

### Valeur de retour

Un indicateur indiquant si l'analyse du document modèle a réussi. L'indicateur retourné n'a de sens que si la valeur de la propriété [`Options`](../options) inclut l'option InlineErrorMessages.

### Voir aussi

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Charge un document modèle depuis le flux source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant vers le flux cible en utilisant les [`LoadSaveOptions`](../../loadsaveoptions) fournis.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStream | Stream | Le flux à partir duquel lire un document modèle. |
| targetStream | Stream | Le flux dans lequel écrire le document résultant. |
| loadSaveOptions | LoadSaveOptions | Spécifie des options supplémentaires pour le chargement et l'enregistrement du document. |
| dataSourceInfos | DataSourceInfo[] | Fournit des informations sur les objets source de données à utiliser. |

### Valeur de retour

Un indicateur indiquant si l'analyse du document modèle a réussi. L'indicateur retourné n'a de sens que si la valeur de la propriété [`Options`](../options) inclut l'option InlineErrorMessages.

### Voir aussi

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
