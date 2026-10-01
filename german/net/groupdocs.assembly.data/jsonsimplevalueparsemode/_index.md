---
title: "JsonSimpleValueParseMode"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Gibt einen Modus zum Parsen einfacher JSON-Werte null, boolean, number, integer und string beim Laden von JSON an. Ein solcher Modus beeinflusst das Parsen von datetime-Werten nicht."
type: docs
weight: 240
url: /de/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

Gibt einen Modus zum Parsen einfacher JSON-Werte (null, boolesch, Zahl, Ganzzahl und Zeichenkette) beim Laden von JSON an. Ein solcher Modus beeinflusst das Parsen von Datums‑ und Zeitwerten nicht.

```csharp
public enum JsonSimpleValueParseMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Loose | `0` | Gibt den Modus an, bei dem die Typen einfacher JSON-Werte anhand ihrer String-Darstellungen beim Parsen ermittelt werden. Beispielsweise wird der Typ von 'prop' aus dem JSON‑Snippet '{ prop: \"123\" }' in diesem Modus als Integer bestimmt. |
| Strict | `1` | Gibt den Modus an, bei dem die Typen einfacher JSON-Werte aus der JSON-Notation selbst ermittelt werden. Beispielsweise wird der Typ von 'prop' aus dem JSON‑Snippet '{ prop: \"123\" }' in diesem Modus als String bestimmt. |

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
