---
title: "GroupDocs.Assembly.Data"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit des classes pour accéder aux données de documents externes à utiliser lors de l'assemblage d'un document."
type: docs
weight: 20
url: /fr/net/groupdocs.assembly.data/
---
Fournit des classes pour accéder aux données de documents externes à utiliser lors de l'assemblage d'un document.

## Classes

| Classe | Description |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | Représente les options pour analyser les données CSV. |
| [CsvDataSource](./csvdatasource) | Fournit un accès aux données d'un fichier CSV ou d'un flux à utiliser lors de l'assemblage d'un document. |
| [DocumentTable](./documenttable) | Fournit un accès aux données d'une seule table (ou feuille de calcul) située dans un document externe à utiliser lors de l'assemblage d'un document. |
| [DocumentTableCollection](./documenttablecollection) | Représente une collection en lecture seule d'objets [`DocumentTable`](../groupdocs.assembly.data/documenttable) d'une instance particulière de [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
| [DocumentTableColumn](./documenttablecolumn) | Représente une colonne unique d'un objet [`DocumentTable`](../groupdocs.assembly.data/documenttable) particulier. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | Représente une collection en lecture seule d'objets [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) d'une instance particulière de [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableLoadArgs](./documenttableloadargs) | Fournit des données pour la méthode [`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle). |
| [DocumentTableOptions](./documenttableoptions) | Fournit un ensemble d'options pour contrôler l'extraction de données d'une table de document. |
| [DocumentTableRelation](./documenttablerelation) | Représente une relation parent-enfant entre deux objets [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | Représente la collection d'objets [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) d'une seule instance de [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
| [DocumentTableSet](./documenttableset) | Fournit un accès aux données de plusieurs tables (ou feuilles de calcul) situées dans un document externe à utiliser lors de l'assemblage d'un document. Permet également de définir des relations parent-enfant pour les tables de document, simplifiant ainsi l'accès aux données liées dans les documents modèles. |
| [JsonDataLoadOptions](./jsondataloadoptions) | Représente les options pour l'analyse des données JSON. |
| [JsonDataSource](./jsondatasource) | Fournit un accès aux données d'un fichier JSON ou d'un flux à utiliser lors de l'assemblage d'un document. |
| [XmlDataLoadOptions](./xmldataloadoptions) | Représente les options de chargement des données XML. |
| [XmlDataSource](./xmldatasource) | Fournit un accès aux données d'un fichier XML ou d'un flux à utiliser lors de l'assemblage d'un document. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | Remplace le chargement par défaut des objets [`DocumentTable`](../groupdocs.assembly.data/documenttable) lors de la création d'une instance de [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
## Énumération

| Énumération | Description |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | Spécifie un mode d'analyse des valeurs simples JSON (null, booléen, nombre, entier et chaîne) lors du chargement du JSON. Un tel mode n'affecte pas l'analyse des valeurs de date‑heure. |

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
