---
title: "BarcodeSettings"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Représente un ensemble de paramètres contrôlant la génération de codes-barres lors de l'assemblage d'un document."
type: docs
weight: 10
url: /fr/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

Représente un ensemble de paramètres contrôlant la génération de codes-barres lors de l'assemblage d'un document.

```csharp
public class BarcodeSettings
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | Obtient ou définit une dimension de base en x, c'est-à-dire la plus petite largeur de l'unité des barres et espaces du code-barres. Mesurée en [`GraphicsUnit`](./graphicsunit). |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | Obtient ou définit une dimension de base en y, c'est-à-dire la plus petite hauteur de l'unité des modules du code-barres 2D. Mesurée en [`GraphicsUnit`](./graphicsunit). |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | Obtient ou définit une unité graphique utilisée pour mesurer [`BaseXDimension`](./basexdimension) et [`BaseYDimension`](./baseydimension). La valeur par défaut est Millimeter. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | Obtient ou définit la résolution horizontale et verticale d'une image de code-barres générée. Mesurée en points par pouce. La valeur par défaut est 96. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | Obtient ou définit une valeur indiquant si une valeur de code-barres invalide doit être corrigée automatiquement (si possible) pour correspondre à la spécification du code-barres ou si une exception doit être levée pour indiquer l'erreur. La valeur par défaut est true. |

### Voir aussi

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
