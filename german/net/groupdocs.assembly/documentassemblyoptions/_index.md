---
title: "DocumentAssemblyOptions"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Gibt Optionen an, die das Verhalten von DocumentAssembler./documentassembler beim Zusammenstellen eines Dokuments steuern."
type: docs
weight: 50
url: /de/net/groupdocs.assembly/documentassemblyoptions/
---
## DocumentAssemblyOptions enumeration

Gibt Optionen an, die das Verhalten von [`DocumentAssembler`](../documentassembler) beim Zusammenstellen eines Dokuments steuern.

```csharp
[Flags]
public enum DocumentAssemblyOptions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Gibt Standardoptionen an. |
| AllowMissingMembers | `1` | Gibt an, dass fehlende Objektmitglieder vom Assembler als Null-Literale behandelt werden sollen. Diese Option wirkt sich nur auf den Zugriff auf Instanz‑ (d. h. nicht‑statische) Objektmitglieder und Erweiterungsmethoden aus. Wenn diese Option nicht gesetzt ist, wirft der Assembler eine Ausnahme, wenn ein fehlendes Objektmitglied gefunden wird. |
| UpdateFieldsAndFormulas | `2` | Gibt an, dass Felder von Ergebnis‑Word‑Processing‑Dokumenten und Formeln von Ergebnis‑Spreadsheet‑Dokumenten vom Assembler aktualisiert werden sollen. |
| RemoveEmptyParagraphs | `4` | Gibt an, dass der Assembler Absätze entfernen soll, die leer werden, nachdem Vorlagensyntax‑Tags entfernt oder durch leere Werte ersetzt wurden. |
| InlineErrorMessages | `8` | Gibt an, dass der Assembler Fehlermeldungen der Vorlagensyntax in Ausgabedokumente einbetten soll. Wenn diese Option nicht gesetzt ist, wirft der Assembler eine Ausnahme, wenn ein Syntaxfehler auftritt. |
| UseSpreadsheetDataTypes | `10` | Bezieht sich ausschließlich auf Spreadsheet‑Dokumente. Gibt an, dass ausgewertete Ausdrucksergebnisse den entsprechenden Spreadsheet‑Datentypen zugeordnet werden sollen, was auch die Standardformatierung in Zellen beeinflusst. Wenn diese Option nicht gesetzt ist, schreibt der Assembler Ausdrucksergebnisse immer als Zeichenketten. Diese Option hat keine Wirkung, wenn Ausdrucksergebnisse mithilfe von Vorlagensyntax formatiert werden – dann werden Ausdrucksergebnisse ebenfalls immer als Zeichenketten geschrieben. |

### Siehe auch

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
