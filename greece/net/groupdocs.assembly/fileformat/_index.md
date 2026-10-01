---
title: "FileFormat"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Καθορίζει τη μορφή ενός αρχείου."
type: docs
weight: 30
url: /el/net/groupdocs.assembly/fileformat/
---
## FileFormat enumeration

Καθορίζει τη μορφή ενός αρχείου.

```csharp
public enum FileFormat
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Unspecified | `0` | Καθορίζει μια μη ορισμένη τιμή. Η προεπιλογή. |
| Doc | `1` | Καθορίζει τη μορφή Microsoft Word 97 - 2007 Binary Document. |
| Dot | `2` | Καθορίζει τη μορφή Microsoft Word 97 - 2007 Binary Template. |
| Docx | `3` | Καθορίζει τη μορφή Office Open XML WordprocessingML Document (χωρίς μακροεντολές). |
| Docm | `4` | Καθορίζει τη μορφή Office Open XML WordprocessingML Macro-Enabled Document. |
| Dotx | `5` | Καθορίζει τη μορφή Office Open XML WordprocessingML Template (χωρίς μακροεντολές). |
| Dotm | `6` | Καθορίζει τη μορφή Office Open XML WordprocessingML Macro-Enabled Template. |
| FlatOpc | `7` | Καθορίζει τη μορφή Office Open XML WordprocessingML που αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| FlatOpcMacroEnabled | `8` | Καθορίζει τη μορφή Office Open XML WordprocessingML Macro-Enabled Document που αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| FlatOpcTemplate | `9` | Καθορίζει τη μορφή Office Open XML WordprocessingML Template (χωρίς μακροεντολές) που αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| FlatOpcTemplateMacroEnabled | `10` | Καθορίζει το Office Open XML WordprocessingML Macro-Enabled Template format stored in a flat XML file instead of a ZIP package. |
| WordML | `11` | Καθορίζει το Microsoft Word 2003 WordprocessingML format. |
| Odt | `12` | Καθορίζει το ODF Text Document format. |
| Ott | `13` | Καθορίζει το ODF Text Document Template format. |
| Xls | `14` | Καθορίζει το Microsoft Excel 97 - 2007 Binary Workbook format. |
| Xlsx | `15` | Καθορίζει το Office Open XML SpreadsheetML Workbook (macro-free) format. |
| Xlsm | `16` | Καθορίζει το Office Open XML SpreadsheetML Macro-Enabled Workbook format. |
| Xltx | `17` | Καθορίζει το Office Open XML SpreadsheetML Template (macro-free) format. |
| Xltm | `18` | Καθορίζει το Office Open XML SpreadsheetML Macro-Enabled Template format. |
| Xlam | `19` | Καθορίζει το Office Open XML SpreadsheetML Macro-Enabled Add-in format. |
| Xlsb | `20` | Καθορίζει το Microsoft Excel 2007 Macro-Enabled Binary File format. |
| SpreadsheetML | `21` | Καθορίζει το Microsoft Excel 2003 SpreadsheetML format. |
| Ods | `22` | Καθορίζει το ODF Spreadsheet format. |
| Ppt | `23` | Καθορίζει το Microsoft PowerPoint 97 - 2007 Binary Presentation format. |
| Pps | `24` | Καθορίζει το Microsoft PowerPoint 97 - 2007 Binary Slide Show format. |
| Pptx | `25` | Καθορίζει το Office Open XML PresentationML Presentation (macro-free) format. |
| Pptm | `26` | Καθορίζει το Office Open XML PresentationML Macro-Enabled Presentation format. |
| Ppsx | `27` | Καθορίζει το Office Open XML PresentationML Slide Show (macro-free) format. |
| Ppsm | `28` | Καθορίζει το Office Open XML PresentationML Macro-Enabled Slide Show format. |
| Potx | `29` | Καθορίζει το Office Open XML PresentationML Template (macro-free) format. |
| Potm | `30` | Καθορίζει το Office Open XML PresentationML Macro-Enabled Template format. |
| Odp | `31` | Καθορίζει το ODF Presentation format. |
| MsgAscii | `32` | Καθορίζει το Microsoft Outlook Message (MSG) format using ASCII character encoding. |
| MsgUnicode | `33` | Καθορίζει το Microsoft Outlook Message (MSG) format using Unicode character encoding. |
| Eml | `34` | Καθορίζει το MIME standard format. |
| Emlx | `35` | Καθορίζει τη μορφή αρχείου προγράμματος Apple Mail.app. |
| Rtf | `36` | Καθορίζει τη μορφή RTF. |
| Text | `37` | Καθορίζει τη μορφή απλού κειμένου. |
| Xml | `38` | Καθορίζει τη μορφή XML μιας γενικής φόρμας. |
| Xaml | `39` | Καθορίζει τη μορφή Extensible Application Markup Language (XAML). |
| XamlPackage | `40` | Καθορίζει τη μορφή πακέτου Extensible Application Markup Language (XAML). |
| Html | `41` | Καθορίζει τη μορφή HTML. |
| Mhtml | `42` | Καθορίζει τη μορφή MHTML (Web archive). |
| Xps | `43` | Καθορίζει τη μορφή XPS (XML Paper Specification). |
| OpenXps | `44` | Καθορίζει τη μορφή OpenXPS (Ecma-388). |
| Pdf | `45` | Καθορίζει τη μορφή PDF (Adobe Portable Document). |
| Epub | `46` | Καθορίζει τη μορφή IDPF EPUB. |
| Ps | `47` | Καθορίζει τη μορφή PS (PostScript). |
| Pcl | `48` | Καθορίζει τη μορφή PCL (Printer Control Language). |
| Svg | `49` | Καθορίζει τη μορφή SVG (Scalable Vector Graphics). |
| Tiff | `50` | Καθορίζει τη μορφή TIFF. |
| Markdown | `51` | Καθορίζει τη μορφή Markdown. |
| Pot | `52` | Καθορίζει τη μορφή Microsoft PowerPoint 97 - 2007 Binary Template. |
| Otp | `53` | Καθορίζει τη μορφή ODF Presentation Template. |
| Xlt | `54` | Καθορίζει τη μορφή Microsoft Excel 97 - 2007 Binary Template. |

### Δείτε επίσης

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
