---
title: "UseReflectionOptimization"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit une valeur indiquant si les appels aux membres de type personnalisés effectués via l'API de réflexion sont optimisés à l'aide de la génération de classes dynamiques ou non. La valeur par défaut est true."
type: docs
weight: 60
url: /fr/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Obtient ou définit une valeur indiquant si les appels aux membres de type personnalisés effectués via l'API de réflexion sont optimisés à l'aide de la génération de classes dynamiques ou non. La valeur par défaut est true.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Remarques

Il existe certains scénarios où il est préférable de désactiver cette optimisation. Par exemple, si vous travaillez constamment avec de petites collections d'éléments de données, le coût de génération dynamique de classes peut être plus perceptible que le coût des appels directs à l'API de réflexion.

### Voir aussi

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
