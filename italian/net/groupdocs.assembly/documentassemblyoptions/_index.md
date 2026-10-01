---
title: "DocumentAssemblyOptions"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Specifica le opzioni che controllano il comportamento di DocumentAssembler./documentassembler durante l'assemblaggio di un documento."
type: docs
weight: 50
url: /it/net/groupdocs.assembly/documentassemblyoptions/
---
## DocumentAssemblyOptions enumeration

Specifica le opzioni che controllano il comportamento di [`DocumentAssembler`](../documentassembler) durante l'assemblaggio di un documento.

```csharp
[Flags]
public enum DocumentAssemblyOptions
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Specifica le opzioni predefinite. |
| AllowMissingMembers | `1` | Specifica che i membri di oggetto mancanti devono essere trattati come letterali null dall'assemblatore. Questa opzione influisce solo sull'accesso ai membri di oggetto di istanza (cioè non statici) e ai metodi di estensione. Se questa opzione non è impostata, l'assemblatore genera un'eccezione quando incontra un membro di oggetto mancante. |
| UpdateFieldsAndFormulas | `2` | Specifica che i campi dei documenti di elaborazione testi risultanti e le formule dei documenti foglio di calcolo risultanti debbano essere aggiornati dall'assemblatore. |
| RemoveEmptyParagraphs | `4` | Specifica che l'assemblatore debba rimuovere i paragrafi che diventano vuoti dopo che i tag di sintassi del modello sono stati rimossi o sostituiti con valori vuoti. |
| InlineErrorMessages | `8` | Specifica che l'assemblatore debba inserire inline i messaggi di errore di sintassi del modello nei documenti di output. Se questa opzione non è impostata, l'assemblatore genera un'eccezione quando incontra un errore di sintassi. |
| UseSpreadsheetDataTypes | `10` | Riguarda solo i documenti Spreadsheet. Specifica che i risultati delle espressioni valutate devono essere mappati ai corrispondenti tipi di dati Spreadsheet, il che influisce anche sulla loro formattazione predefinita nelle celle. Se questa opzione non è impostata, i risultati delle espressioni sono sempre scritti come stringhe dall'assemblatore. Questa opzione non ha effetto quando i risultati delle espressioni sono formattati usando la sintassi del modello – i risultati delle espressioni sono comunque sempre scritti come stringhe. |

### Vedi anche

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
