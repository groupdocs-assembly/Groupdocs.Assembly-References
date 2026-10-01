---
title: "GroupDocs.Assembly.Data"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce classi per accedere ai dati di documenti esterni da utilizzare durante l'assemblaggio di un documento."
type: docs
weight: 20
url: /it/net/groupdocs.assembly.data/
---
Fornisce classi per accedere ai dati di documenti esterni da utilizzare durante l'assemblaggio di un documento.

## Classi

| Classe | Descrizione |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | Rappresenta le opzioni per l'analisi dei dati CSV. |
| [CsvDataSource](./csvdatasource) | Fornisce l'accesso ai dati di un file CSV o di uno stream da utilizzare durante l'assemblaggio di un documento. |
| [DocumentTable](./documenttable) | Fornisce l'accesso ai dati di una singola tabella (o foglio di calcolo) situata in un documento esterno da utilizzare durante l'assemblaggio di un documento. |
| [DocumentTableCollection](./documenttablecollection) | Rappresenta una collezione di sola lettura di oggetti [`DocumentTable`](../groupdocs.assembly.data/documenttable) di una specifica istanza di [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
| [DocumentTableColumn](./documenttablecolumn) | Rappresenta una singola colonna di un particolare oggetto [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | Rappresenta una collezione di sola lettura di oggetti [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) di una specifica istanza di [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableLoadArgs](./documenttableloadargs) | Fornisce i dati per il metodo [`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle). |
| [DocumentTableOptions](./documenttableoptions) | Fornisce un insieme di opzioni per controllare l'estrazione dei dati da una tabella di documento. |
| [DocumentTableRelation](./documenttablerelation) | Rappresenta una relazione padre-figlio tra due oggetti [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | Rappresenta la collezione di oggetti [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) di una singola istanza di [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
| [DocumentTableSet](./documenttableset) | Fornisce l'accesso ai dati di più tabelle (o fogli di calcolo) situate in un documento esterno da utilizzare durante l'assemblaggio di un documento. Inoltre, consente di definire relazioni padre-figlio per le tabelle di documento semplificando così l'accesso ai dati correlati all'interno dei documenti modello. |
| [JsonDataLoadOptions](./jsondataloadoptions) | Rappresenta le opzioni per l'analisi dei dati JSON. |
| [JsonDataSource](./jsondatasource) | Fornisce l'accesso ai dati di un file JSON o di uno stream da utilizzare durante l'assemblaggio di un documento. |
| [XmlDataLoadOptions](./xmldataloadoptions) | Rappresenta le opzioni per il caricamento dei dati XML. |
| [XmlDataSource](./xmldatasource) | Fornisce l'accesso ai dati di un file XML o di uno stream da utilizzare durante l'assemblaggio di un documento. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | Sovrascrive il caricamento predefinito di oggetti [`DocumentTable`](../groupdocs.assembly.data/documenttable) durante la creazione di un'istanza di [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | Specifica una modalità per l'analisi dei valori semplici JSON (null, booleano, numero, intero e stringa) durante il caricamento di JSON. Tale modalità non influisce sull'analisi dei valori data-ora. |

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
