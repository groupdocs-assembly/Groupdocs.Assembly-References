---
title: "DocumentAssembler"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona rutinas para rellenar documentos plantilla con datos y un conjunto de configuraciones para controlar estas rutinas."
type: docs
weight: 40
url: /es/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

Proporciona rutinas para rellenar documentos plantilla con datos y un conjunto de configuraciones para controlar estas rutinas.

```csharp
public class DocumentAssembler
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocumentAssembler](documentassembler)() | Inicializa una nueva instancia de esta clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | Obtiene un conjunto de configuraciones que controlan la generación de códigos de barras al ensamblar un documento. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | Obtiene un conjunto no ordenado (es decir, una colección de elementos únicos) que contiene objetos Type cuyos nombres totalmente o parcialmente calificados pueden usarse dentro de plantillas de documentos procesadas por esta instancia del ensamblador para invocar los miembros estáticos de los tipos correspondientes, realizar conversiones de tipo, etc. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | Obtiene o establece un conjunto de indicadores que controlan el comportamiento de esta instancia de [`DocumentAssembler`](../documentassembler) al ensamblar un documento. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | Obtiene o establece un valor que indica si las invocaciones de miembros de tipos personalizados realizadas a través de la API de reflexión se optimizan mediante generación dinámica de clases o no. El valor predeterminado es true. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | Carga un documento de plantilla desde el flujo de origen especificado, rellena el documento de plantilla con datos de la(s) fuente(s) única(s) o múltiple(s) especificada(s), y almacena el documento resultante en el flujo de destino usando las [`LoadSaveOptions`](../loadsaveoptions) predeterminadas. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | Carga un documento de plantilla desde la ruta de origen especificada, rellena el documento de plantilla con datos de la(s) fuente(s) única(s) o múltiple(s) especificada(s), y almacena el documento resultante en la ruta de destino usando las [`LoadSaveOptions`](../loadsaveoptions) predeterminadas. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | Carga un documento de plantilla desde el flujo de origen especificado, rellena el documento de plantilla con datos de la(s) fuente(s) única(s) o múltiple(s) especificada(s), y almacena el documento resultante en el flujo de destino usando las [`LoadSaveOptions`](../loadsaveoptions) proporcionadas. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | Carga un documento de plantilla desde la ruta de origen especificada, rellena el documento de plantilla con datos de la(s) fuente(s) única(s) o múltiple(s) especificada(s), y almacena el documento resultante en la ruta de destino usando las [`LoadSaveOptions`](../loadsaveoptions) proporcionadas. |

### Ver también

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
