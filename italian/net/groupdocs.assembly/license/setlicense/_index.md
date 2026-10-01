---
title: "SetLicense"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Concede licenza al componente."
type: docs
weight: 30
url: /it/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Concede licenza al componente.

```csharp
public void SetLicense(string licenseName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | String | Può essere un nome file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

### Osservazioni

Cerca di trovare la licenza nei seguenti percorsi:

1. Percorso esplicito.

2. La cartella che contiene l'assembly del componente GroupDocs.

3. La cartella che contiene l'assembly chiamante del client.

4. La cartella che contiene l'assembly di ingresso (avvio).

5. Una risorsa incorporata nell'assembly chiamante del client.

### Vedi anche

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

Concede licenza al componente.

```csharp
public void SetLicense(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Uno stream che contiene la licenza. |

### Osservazioni

Usa questo metodo per caricare una licenza da uno stream.

### Vedi anche

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
