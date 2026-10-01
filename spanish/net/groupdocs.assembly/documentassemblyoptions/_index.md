---
title: "DocumentAssemblyOptions"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Especifica opciones que controlan el comportamiento de DocumentAssembler./documentassembler al ensamblar un documento."
type: docs
weight: 50
url: /es/net/groupdocs.assembly/documentassemblyoptions/
---
## DocumentAssemblyOptions enumeration

Especifica opciones que controlan el comportamiento de [`DocumentAssembler`](../documentassembler) al ensamblar un documento.

```csharp
[Flags]
public enum DocumentAssemblyOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Especifica opciones predeterminadas. |
| AllowMissingMembers | `1` | Especifica que los miembros de objeto faltantes deben ser tratados como literales nulos por el ensamblador. Esta opción afecta solo el acceso a los miembros de objeto de instancia (es decir, no estáticos) y a los métodos de extensión. Si esta opción no está establecida, el ensamblador lanza una excepción cuando encuentra un miembro de objeto faltante. |
| UpdateFieldsAndFormulas | `2` | Especifica que los campos de los documentos de procesamiento de texto resultantes y las fórmulas de los documentos de hoja de cálculo resultantes deben ser actualizados por el ensamblador. |
| RemoveEmptyParagraphs | `4` | Especifica que el ensamblador debe eliminar los párrafos que quedan vacíos después de que las etiquetas de sintaxis de plantilla se eliminen o se reemplacen por valores vacíos. |
| InlineErrorMessages | `8` | Especifica que el ensamblador debe incrustar los mensajes de error de sintaxis de plantilla en los documentos de salida. Si esta opción no está establecida, el ensamblador lanza una excepción cuando encuentra un error de sintaxis. |
| UseSpreadsheetDataTypes | `10` | Se aplica solo a documentos de hoja de cálculo. Especifica que los resultados de expresiones evaluadas deben mapearse a los tipos de datos de hoja de cálculo correspondientes, lo que también afecta su formato predeterminado dentro de las celdas. Si esta opción no está establecida, el ensamblador siempre escribe los resultados de expresiones como cadenas. Esta opción no tiene efecto cuando los resultados de expresiones se formatean usando la sintaxis de plantilla; en ese caso, los resultados de expresiones también se escriben siempre como cadenas. |

### Ver también

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
