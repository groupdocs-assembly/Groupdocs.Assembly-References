---
title: "ResourceSaveFolder"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece una ruta a una carpeta para almacenar archivos de recursos externos mientras un documento ensamblado cargado desde un formato no HTML se guarda en HTML. El valor predeterminado es una cadena vacía."
type: docs
weight: 30
url: /es/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

Obtiene o establece una ruta a una carpeta para almacenar los archivos de recursos externos mientras un documento ensamblado cargado desde un formato no HTML se guarda en HTML. El valor predeterminado es una cadena vacía.

```csharp
public string ResourceSaveFolder { get; set; }
```

### Observaciones

Por defecto, al guardar un documento ensamblado en un archivo HTML, los archivos de recursos externos se almacenan en una carpeta que tiene el mismo nombre que el archivo HTML sin extensión más el sufijo "_files". Esta carpeta se encuentra en la misma carpeta que el archivo HTML. Sin embargo, esto no se puede hacer al guardar un documento ensamblado en un flujo HTML. Establezca esta propiedad para especificar una ruta a una carpeta para almacenar archivos de recursos externos al guardar un documento ensamblado en un flujo HTML o para sobrescribir la carpeta predeterminada al guardar un documento ensamblado en un archivo HTML.

Un valor de esta propiedad se ignora si un documento ensamblado que se está guardando en HTML fue cargado también desde HTML (los archivos de recursos externos no se almacenan y los enlaces a ellos no se modifican).

### Ver también

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
