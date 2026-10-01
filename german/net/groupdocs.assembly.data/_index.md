---
title: "GroupDocs.Assembly.Data"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Klassen zum Zugriff auf Daten externer Dokumente bereit, die beim Zusammenstellen eines Dokuments verwendet werden."
type: docs
weight: 20
url: /de/net/groupdocs.assembly.data/
---
Stellt Klassen zum Zugriff auf Daten externer Dokumente bereit, die beim Zusammenstellen eines Dokuments verwendet werden.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | Stellt Optionen zum Parsen von CSV‑Daten dar. |
| [CsvDataSource](./csvdatasource) | Stellt Zugriff auf Daten einer CSV-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden. |
| [DocumentTable](./documenttable) | Stellt Zugriff auf Daten einer einzelnen Tabelle (oder Tabellenkalkulation) in einem externen Dokument bereit, die beim Zusammenstellen eines Dokuments verwendet werden. |
| [DocumentTableCollection](./documenttablecollection) | Stellt eine schreibgeschützte Sammlung von [`DocumentTable`](../groupdocs.assembly.data/documenttable)-Objekten einer bestimmten [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset)-Instanz dar. |
| [DocumentTableColumn](./documenttablecolumn) | Stellt eine einzelne Spalte eines bestimmten [`DocumentTable`](../groupdocs.assembly.data/documenttable)-Objekts dar. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | Stellt eine schreibgeschützte Sammlung von [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn)-Objekten einer bestimmten [`DocumentTable`](../groupdocs.assembly.data/documenttable)-Instanz dar. |
| [DocumentTableLoadArgs](./documenttableloadargs) | Stellt Daten für die Methode [`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle) bereit. |
| [DocumentTableOptions](./documenttableoptions) | Stellt eine Reihe von Optionen zur Steuerung der Datenextraktion aus einer Dokumenttabelle bereit. |
| [DocumentTableRelation](./documenttablerelation) | Stellt eine Eltern‑Kind-Beziehung zwischen zwei [`DocumentTable`](../groupdocs.assembly.data/documenttable)-Objekten dar. |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | Stellt die Sammlung von [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation)-Objekten einer einzelnen [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset)-Instanz dar. |
| [DocumentTableSet](./documenttableset) | Stellt Zugriff auf Daten mehrerer Tabellen (oder Tabellenkalkulationen) in einem externen Dokument bereit, die beim Zusammenstellen eines Dokuments verwendet werden. Außerdem ermöglicht es, Eltern‑Kind-Beziehungen für die Dokumenttabellen zu definieren, wodurch der Zugriff auf verwandte Daten innerhalb von Vorlagendokumenten vereinfacht wird. |
| [JsonDataLoadOptions](./jsondataloadoptions) | Stellt Optionen für das Parsen von JSON-Daten dar. |
| [JsonDataSource](./jsondatasource) | Stellt Zugriff auf Daten einer JSON-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden. |
| [XmlDataLoadOptions](./xmldataloadoptions) | Stellt Optionen für das Laden von XML-Daten dar. |
| [XmlDataSource](./xmldatasource) | Stellt Zugriff auf Daten einer XML-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | Überschreibt das Standardladen von [`DocumentTable`](../groupdocs.assembly.data/documenttable)-Objekten beim Erstellen einer [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset)-Instanz. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | Gibt einen Modus zum Parsen einfacher JSON-Werte (null, boolesch, Zahl, Ganzzahl und Zeichenkette) beim Laden von JSON an. Ein solcher Modus beeinflusst das Parsen von Datums‑ und Zeitwerten nicht. |

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
