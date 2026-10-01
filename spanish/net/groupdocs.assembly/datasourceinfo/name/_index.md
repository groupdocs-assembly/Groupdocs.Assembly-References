---
title: "Nombre"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece el nombre del objeto de origen de datos que se utilizará para acceder al objeto de origen de datos en un documento de plantilla."
type: docs
weight: 30
url: /es/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

Obtiene o establece el nombre del objeto de origen de datos que se utilizará para acceder al objeto de origen de datos en un documento de plantilla.

```csharp
public string Name { get; set; }
```

### Observaciones

Cuando se especifica el nombre del objeto de origen de datos, puede acceder al objeto de origen de datos y a sus miembros en un documento de plantilla usando el nombre.

Cuando el nombre del objeto de origen de datos es nulo o vacío, aún puede acceder a los miembros del objeto de origen de datos en un documento de plantilla usando el acceso a miembros del objeto de contexto (consulte Referencia de Sintaxis de Plantilla para más información), pero no puede acceder al propio objeto de origen de datos.

Al pasar múltiples instancias de [`DataSourceInfo`](../../datasourceinfo) a [`DocumentAssembler`](../../documentassembler), solo el nombre del primer objeto de origen de datos puede ser nulo o vacío. Los nombres del resto deben especificarse y ser únicos.

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
