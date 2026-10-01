---
title: "LoadSaveOptions"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Especifica opciones adicionales para cargar y guardar un documento que se va a ensamblar."
type: docs
weight: 80
url: /es/net/groupdocs.assembly/loadsaveoptions/
---
## LoadSaveOptions class

Especifica opciones adicionales para cargar y guardar un documento que se va a ensamblar.

```csharp
public class LoadSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LoadSaveOptions](loadsaveoptions#constructor)() | Crea una nueva instancia de esta clase sin especificar ninguna propiedad. |
| [LoadSaveOptions](loadsaveoptions#constructor_1)(FileFormat) | Crea una nueva instancia de esta clase con el formato de archivo especificado para guardar un documento ensamblado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ResourceLoadBaseUri](../../groupdocs.assembly/loadsaveoptions/resourceloadbaseuri) { get; set; } | Obtiene o establece una URI base para resolver los URI relativos de los archivos de recursos externos a URI absolutos mientras se carga un documento de plantilla HTML que será ensamblado y guardado en un formato no HTML. El valor predeterminado es una cadena vacía. |
| [ResourceSaveFolder](../../groupdocs.assembly/loadsaveoptions/resourcesavefolder) { get; set; } | Obtiene o establece una ruta a una carpeta para almacenar los archivos de recursos externos mientras un documento ensamblado cargado desde un formato no HTML se guarda en HTML. El valor predeterminado es una cadena vacía. |
| [SaveFormat](../../groupdocs.assembly/loadsaveoptions/saveformat) { get; set; } | Obtiene o establece un formato de archivo para guardar un documento ensamblado. No especificado es el valor predeterminado. |

### Ver también

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
