---
title: UseReflectionOptimization
second_title: Referencia de API de GroupDocs.Assembly para .NET
description: Obtiene o establece un valor que indica si las invocaciones de miembros de tipo personalizado realizadas a través de la API de reflexión están optimizadas mediante la generación de clases dinámicas o no. El valor predeterminado es verdadero.
type: docs
weight: 60
url: /es/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

Obtiene o establece un valor que indica si las invocaciones de miembros de tipo personalizado realizadas a través de la API de reflexión están optimizadas mediante la generación de clases dinámicas o no. El valor predeterminado es verdadero.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### Observaciones

Hay algunos escenarios en los que es preferible deshabilitar esta optimización. Por ejemplo, si está tratando con pequeñas colecciones de elementos de datos todo el tiempo, entonces una sobrecarga de generación de clases dinámicas puede ser más notable que una sobrecarga de llamadas API de reflexión directa.

### Ver también

* class [DocumentAssembler](../../documentassembler)
* espacio de nombres [GroupDocs.Assembly](../../documentassembler)
* asamblea [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
