---
title: "BaseYDimension"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit une y‑dimension de base qui est la plus petite hauteur de l’unité des modules de code‑barres 2D. Mesurée en GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit."
type: docs
weight: 20
url: /fr/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

Obtient ou définit une y‑dimension de base, c’est‑à‑dire la plus petite hauteur de l’unité des modules de code‑barres 2D. Mesurée en [`GraphicsUnit`](../graphicsunit).

```csharp
public float BaseYDimension { get; set; }
```

### Remarques

Les codes‑barres de certains types (comme le Data Matrix) peuvent ignorer la y‑dimension et utiliser la x‑dimension pour les unités de largeur et de hauteur.

Lorsque le redimensionnement du code‑barres est appliqué via un modèle, une y‑dimension réelle est calculée à partir de la y‑dimension de base et d’un facteur d’échelle.

### Voir aussi

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
