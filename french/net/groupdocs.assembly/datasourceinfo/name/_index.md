---
title: "Nom"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit le nom de l'objet source de données à utiliser pour accéder à l'objet source de données dans un document modèle."
type: docs
weight: 30
url: /fr/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

Obtient ou définit le nom de l'objet source de données à utiliser pour accéder à l'objet source de données dans un document modèle.

```csharp
public string Name { get; set; }
```

### Remarques

Lorsque le nom de l'objet source de données est spécifié, vous pouvez accéder à l'objet source de données et à ses membres dans un document modèle en utilisant le nom.

Lorsque le nom de l'objet source de données est nul ou vide, vous pouvez toujours accéder aux membres de l'objet source de données dans un document modèle en utilisant l'accès aux membres de l'objet de contexte (voir Référence de la syntaxe du modèle pour plus d'informations), mais vous ne pouvez pas accéder à l'objet source de données lui‑même.

Lors du passage de plusieurs instances de [`DataSourceInfo`](../../datasourceinfo) à [`DocumentAssembler`](../../documentassembler), seul le nom du premier objet source de données peut être nul ou vide. Les noms des autres doivent être spécifiés et uniques.

### Voir aussi

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
