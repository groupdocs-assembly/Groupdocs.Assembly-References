---
title: GroupDocs.Assembly.Data
second_title: GroupDocs.Assembly för .NET API-referens
description: Tillhandahåller klasser för åtkomst till data från externa dokument som ska användas när ett dokument sammanställs.
type: docs
weight: 20
url: /sv/net/groupdocs.assembly.data/
---
Tillhandahåller klasser för åtkomst till data från externa dokument som ska användas när ett dokument sammanställs.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | Representerar alternativ för att analysera CSV-data. |
| [CsvDataSource](./csvdatasource) | Ger tillgång till data från en CSV-fil eller ström som ska användas när ett dokument sammanställs. |
| [DocumentTable](./documenttable) | Ger tillgång till data från en enstaka tabell (eller kalkylblad) som finns i ett externt dokument som ska användas medan sammanställer ett dokument. |
| [DocumentTableCollection](./documenttablecollection) | Representerar en skrivskyddad samling av[`DocumentTable`](../groupdocs.assembly.data/documenttable) föremål för en viss[`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) instans. |
| [DocumentTableColumn](./documenttablecolumn) | Representerar en enda kolumn av en viss[`DocumentTable`](../groupdocs.assembly.data/documenttable) objekt. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | Representerar en skrivskyddad samling av[`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) objekt av en viss [`DocumentTable`](../groupdocs.assembly.data/documenttable) instans. |
| [DocumentTableLoadArgs](./documenttableloadargs) | Tillhandahåller data för[`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle) metod. |
| [DocumentTableOptions](./documenttableoptions) | Ger en uppsättning alternativ för att kontrollera extrahering av data från en dokumenttabell. |
| [DocumentTableRelation](./documenttablerelation) | Representerar en förälder-barn-relation mellan två[`DocumentTable`](../groupdocs.assembly.data/documenttable) objekt. |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | Representerar samlingen av[`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) objekt av en singel[`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) instans. |
| [DocumentTableSet](./documenttableset) | Ger åtkomst till data från flera tabeller (eller kalkylblad) som finns i ett externt dokument som ska användas medan sammanställer ett dokument. Möjliggör också att definiera överordnade-underordnade relationer för dokumenttabellerna och därmed förenkla åtkomst till relaterade data i malldokument. |
| [JsonDataLoadOptions](./jsondataloadoptions) | Representerar alternativ för att analysera JSON-data. |
| [JsonDataSource](./jsondatasource) | Ger tillgång till data från en JSON-fil eller ström som ska användas när ett dokument sammanställs. |
| [XmlDataLoadOptions](./xmldataloadoptions) | Representerar alternativ för XML-dataladdning. |
| [XmlDataSource](./xmldatasource) | Ger tillgång till data från en XML-fil eller ström som ska användas när ett dokument sammanställs. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | Åsidosätter standardladdning av[`DocumentTable`](../groupdocs.assembly.data/documenttable) objekt medan du skapar en[`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) instans. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | Anger ett läge för att analysera JSON enkla värden (null, boolean, nummer, heltal och sträng) när JSON laddas. Ett sådant läge påverkar inte analysen av datum-tid-värden. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->