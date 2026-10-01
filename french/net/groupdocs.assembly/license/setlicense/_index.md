---
title: "SetLicense"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Licence le composant."
type: docs
weight: 30
url: /fr/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licenseName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | String | Peut être un nom de fichier complet ou court ou le nom d'une ressource incorporée. Utilisez une chaîne vide pour passer en mode d'évaluation. |

### Remarques

Essaie de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier contenant l'assembly du composant GroupDocs.

3. Le dossier contenant l'assembly appelant du client.

4. Le dossier contenant l'assembly d'entrée (démarrage).

5. Une ressource incorporée dans l'assembly appelant du client.

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

Licence le composant.

```csharp
public void SetLicense(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Un flux qui contient la licence. |

### Remarques

Utilisez cette méthode pour charger une licence depuis un flux.

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
