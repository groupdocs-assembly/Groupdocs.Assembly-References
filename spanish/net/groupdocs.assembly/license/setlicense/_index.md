---
title: "SetLicense"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Licencia el componente."
type: docs
weight: 30
url: /es/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licencia el componente.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| licenseName | String | Puede ser un nombre de archivo completo o corto, o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación. |

### Observaciones

Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta que contiene el ensamblado del componente GroupDocs.

3. La carpeta que contiene el ensamblado que llama el cliente.

4. La carpeta que contiene el ensamblado de entrada (inicio).

5. Un recurso incrustado en el ensamblado que llama el cliente.

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

Licencia el componente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo que contiene la licencia. |

### Observaciones

Utilice este método para cargar una licencia desde un flujo.

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
