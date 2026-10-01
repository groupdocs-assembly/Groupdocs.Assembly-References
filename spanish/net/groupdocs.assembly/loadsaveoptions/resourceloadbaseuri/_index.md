---
title: "ResourceLoadBaseUri"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece una URI base para resolver archivos de recursos externos, convirtiendo URIs relativas en absolutas mientras se carga un documento plantilla HTML que será ensamblado y guardado en un formato no HTML. El valor predeterminado es una cadena vacía."
type: docs
weight: 20
url: /es/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

Obtiene o establece una URI base para resolver los URI relativos de los archivos de recursos externos a URI absolutos mientras se carga un documento de plantilla HTML que será ensamblado y guardado en un formato no HTML. El valor predeterminado es una cadena vacía.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### Observaciones

Al cargar un documento HTML desde un archivo, su carpeta contenedora se usa como URI base de forma predeterminada, lo que no puede suceder al cargar un documento HTML desde un flujo. Establezca esta propiedad para especificar una URI base al cargar un documento HTML desde un flujo o para sobrescribir la URI base predeterminada al cargar un documento HTML desde un archivo.

Un valor de esta propiedad se ignora en los siguientes casos:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### Ver también

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
