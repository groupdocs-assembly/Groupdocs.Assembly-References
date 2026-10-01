---
title: "DocumentAssembler"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Routinen zum Befüllen von Vorlagendokumenten mit Daten sowie einen Satz von Einstellungen zur Steuerung dieser Routinen bereit."
type: docs
weight: 40
url: /de/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

Stellt Routinen zum Befüllen von Vorlagendokumenten mit Daten sowie einen Satz von Einstellungen zur Steuerung dieser Routinen bereit.

```csharp
public class DocumentAssembler
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DocumentAssembler](documentassembler)() | Initialisiert eine neue Instanz dieser Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | Ruft eine Menge von Einstellungen ab, die die Barcode-Erstellung beim Zusammenstellen eines Dokuments steuern. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | Ruft ein ungeordnetes Set (das heißt, eine Sammlung eindeutiger Elemente) ab, das Type-Objekte enthält, deren vollständig oder teilweise qualifizierte Namen innerhalb von Dokumentvorlagen, die von dieser Assembler-Instanz verarbeitet werden, verwendet werden können, um die statischen Mitglieder der entsprechenden Typen aufzurufen, Typumwandlungen durchzuführen usw. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | Ruft die Menge von Flags ab oder legt sie fest, die das Verhalten dieser [`DocumentAssembler`](../documentassembler)-Instanz beim Zusammenstellen eines Dokuments steuern. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Aufrufe von benutzerdefinierten Typmitgliedern, die über die Reflection-API durchgeführt werden, mithilfe dynamischer Klassengenerierung optimiert werden oder nicht. Der Standardwert ist true. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | Lädt ein Vorlagendokument aus dem angegebenen Quell-Stream, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument in den Ziel-Stream unter Verwendung der Standard-[`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | Lädt ein Vorlagendokument aus dem angegebenen Quellpfad, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument im Zielpfad unter Verwendung der Standard-[`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | Lädt ein Vorlagendokument aus dem angegebenen Quell-Stream, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument in den Ziel-Stream unter Verwendung der angegebenen [`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | Lädt ein Vorlagendokument aus dem angegebenen Quellpfad, füllt das Vorlagendokument mit Daten aus den angegebenen einzelnen oder mehreren Quellen und speichert das Ergebnisdokument im Zielpfad unter Verwendung der angegebenen [`LoadSaveOptions`](../loadsaveoptions). |

### Siehe auch

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
