---
title: XmlDataSource
second_title: GroupDocs.Assembly för .NET API-referens
description: Ger tillgång till data från en XMLfil eller ström som ska användas när ett dokument sammanställs.
type: docs
weight: 180
url: /sv/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

Ger tillgång till data från en XML-fil eller ström som ska användas när ett dokument sammanställs.

```csharp
public class XmlDataSource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | Skapar en ny datakälla med data från en XML-ström med standardalternativ för XML-dataladdning. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | Skapar en ny datakälla med data från en XML-fil med standardalternativ för XML-dataladdning. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | Skapar en ny datakälla med data från en XML-ström med hjälp av en XML Schema Definition-ström. Standard options används för XML-dataladdning. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | Skapar en ny datakälla med data från en XML-ström med de angivna alternativen för XML-dataladdning. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | Skapar en ny datakälla med data från en XML-fil med hjälp av en XML Schema Definition-fil. Standard options används för XML-dataladdning. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | Skapar en ny datakälla med data från en XML-fil med de angivna alternativen för XML-dataladdning. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | Skapar en ny datakälla med data från en XML-ström med hjälp av en XML Schema Definition-ström. De specificerade -alternativen används för XML-dataladdning. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | Skapar en ny datakälla med data från en XML-fil med hjälp av en XML Schema Definition-fil. De specificerade -alternativen används för XML-dataladdning. |

### Anmärkningar

För att komma åt data för motsvarande fil eller ström medan du sammanställer ett dokument, skicka en instans av den här klassen as en datakälla till en av[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument överbelastningar.

I malldokument, om ett XML-element på toppnivå endast innehåller en lista med element av samma typ, en[`XmlDataSource`](../xmldatasource) instans bör behandlas på samma sätt som om det vore aDataTable exempel. Annars, en[`XmlDataSource`](../xmldatasource) instans bör behandlas på samma sätt som om det vore enDataRowexempel. För mer information, se mallsyntaxreferens (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

När XML Schema Definition skickas till en konstruktor av denna klass, bestäms datatyper av värden för enkla XML-element och attribut enligt schemat. Så i malldokument kan du arbeta med inskrivna värden snarare än bara strängar.

När XML Schema Definition inte skickas till en konstruktor av denna klass, bestäms datatyper av värden för enkla XML-element och attribut automatiskt efter deras strängrepresentationer. Så i malldokument kan du arbeta med inskrivna värden också i det här fallet. Motorn kan automatiskt känna igen värden av följande typer:

* Nullable
* Nullable
* Nullable
* Nullable
* String

Observera att för att automatisk igenkänning av datatyper ska fungera bör strängrepresentationer av värden för enkla XML-element och attribut skapas med invarianta kulturinställningar.

För att åsidosätta standardbeteendet för XML-dataladdning, initiera och skicka ett[`XmlDataLoadOptions`](../xmldataloadoptions) instans till en konstruktor av denna klass.

### Se även

* namnutrymme [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* hopsättning [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->