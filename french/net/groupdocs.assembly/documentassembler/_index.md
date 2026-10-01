---
title: "DocumentAssembler"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit des routines pour remplir les documents modèles avec des données et un ensemble de paramètres pour contrôler ces routines."
type: docs
weight: 40
url: /fr/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

Fournit des routines pour remplir les documents modèles avec des données et un ensemble de paramètres pour contrôler ces routines.

```csharp
public class DocumentAssembler
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DocumentAssembler](documentassembler)() | Initialise une nouvelle instance de cette classe. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | Obtient un ensemble de paramètres contrôlant la génération de codes-barres lors de l'assemblage d'un document. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | Obtient un ensemble non ordonné (c’est‑à‑dire une collection d’éléments uniques) contenant des objets Type dont les noms entièrement ou partiellement qualifiés peuvent être utilisés dans les modèles de document traités par cette instance d'assembleur pour invoquer les membres statiques des types correspondants, effectuer des conversions de type, etc. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | Obtient ou définit un ensemble de drapeaux contrôlant le comportement de cette instance de [`DocumentAssembler`](../documentassembler) lors de l'assemblage d'un document. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | Obtient ou définit une valeur indiquant si les appels aux membres de type personnalisés effectués via l'API de réflexion sont optimisés à l'aide de la génération de classes dynamiques ou non. La valeur par défaut est true. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | Charge un document modèle depuis le flux source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant dans le flux cible en utilisant les [`LoadSaveOptions`](../loadsaveoptions) par défaut. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | Charge un document modèle depuis le chemin source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant dans le chemin cible en utilisant les [`LoadSaveOptions`](../loadsaveoptions) par défaut. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | Charge un document modèle depuis le flux source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant dans le flux cible en utilisant les [`LoadSaveOptions`](../loadsaveoptions) fournis. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | Charge un document modèle depuis le chemin source spécifié, remplit le document modèle avec les données provenant de la ou des sources spécifiées, et enregistre le document résultant dans le chemin cible en utilisant les [`LoadSaveOptions`](../loadsaveoptions) fournis. |

### Voir aussi

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
