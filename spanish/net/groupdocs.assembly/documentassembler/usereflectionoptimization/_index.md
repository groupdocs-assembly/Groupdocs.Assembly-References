---
title: "UseReflectionOptimization"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece un valor que indica si las invocaciones de miembros de tipos personalizados realizadas a través de la API de reflexión se optimizan mediante generación dinámica de clases o no. El valor predeterminado es true."
type: docs
weight: 60
url: /es/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Obtiene o establece un valor que indica si las invocaciones de miembros de tipos personalizados realizadas a través de la API de reflexión se optimizan mediante generación dinámica de clases o no. El valor predeterminado es true.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Observaciones

Hay algunos escenarios en los que es preferible desactivar esta optimización. Por ejemplo, si trabajas con pequeñas colecciones de elementos de datos todo el tiempo, entonces la sobrecarga de generación dinámica de clases puede ser más notable que la sobrecarga de llamadas directas a la API de reflexión.

### Ver también

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
