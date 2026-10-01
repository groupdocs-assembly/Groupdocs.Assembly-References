---
title: "SetLicense"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Lizenziert die Komponente."
type: docs
weight: 30
url: /de/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | String | Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie einen leeren String, um in den Evaluierungsmodus zu wechseln. |

### Hinweise

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die GroupDocs‑Komponenten‑Assembly enthält.

3. Der Ordner, der die Aufruf‑Assembly des Clients enthält.

4. Der Ordner, der die Einstiegs‑(Start‑)Assembly enthält.

5. Eine eingebettete Ressource in der Aufruf‑Assembly des Clients.

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream, der die Lizenz enthält. |

### Hinweise

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
