---
title: "UseReflectionOptimization"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder setzt einen Wert, der angibt, ob Aufrufe von benutzerdefinierten Typmitgliedern, die über die Reflection-API durchgeführt werden, mithilfe dynamischer Klassengenerierung optimiert werden oder nicht. Der Standardwert ist true."
type: docs
weight: 60
url: /de/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Liest oder setzt einen Wert, der angibt, ob Aufrufe von benutzerdefinierten Typmitgliedern, die über die Reflection-API durchgeführt werden, mithilfe dynamischer Klassengenerierung optimiert werden oder nicht. Der Standardwert ist true.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Hinweise

Es gibt einige Szenarien, in denen es vorzuziehen ist, diese Optimierung zu deaktivieren. Zum Beispiel, wenn Sie ständig mit kleinen Sammlungen von Datenelementen arbeiten, kann der Aufwand für die dynamische Klassengenerierung auffälliger sein als der Aufwand für direkte Reflection-API-Aufrufe.

### Siehe auch

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
