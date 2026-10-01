---
title: "Medido"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona métodos para trabajar con licencias por consumo."
type: docs
weight: 90
url: /es/net/groupdocs.assembly/metered/
---
## Metered class

Proporciona métodos para trabajar con licencias por consumo.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered)() | Crea una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | Habilita la licencia medida para el componente especificando las claves públicas y privadas de medida apropiadas. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | Devuelve el número de créditos consumidos actualmente. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | Devuelve el número de megabytes consumidos actualmente. |

### Ejemplos

En este ejemplo, se intenta establecer claves públicas y privadas de medida:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ver también

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
