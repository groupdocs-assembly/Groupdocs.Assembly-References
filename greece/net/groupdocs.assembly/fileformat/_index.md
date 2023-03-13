---
title: FileFormat
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Καθορίζει τη μορφή ενός αρχείου.
type: docs
weight: 220
url: /el/net/groupdocs.assembly/fileformat/
---
## FileFormat enumeration

Καθορίζει τη μορφή ενός αρχείου.

```csharp
public enum FileFormat
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Unspecified | `0` | Καθορίζει μια μη καθορισμένη τιμή. Η προεπιλογή. |
| Doc | `1` | Καθορίζει τη μορφή δυαδικού εγγράφου Microsoft Word 97 - 2007. |
| Dot | `2` | Καθορίζει τη μορφή δυαδικού προτύπου Microsoft Word 97 - 2007. |
| Docx | `3` | Καθορίζει τη μορφή του Office Open XML WordprocessingML Document (χωρίς μακροεντολή). |
| Docm | `4` | Καθορίζει τη μορφή εγγράφου Open XML WordprocessingML με δυνατότητα Macro. |
| Dotx | `5` | Καθορίζει τη μορφή του Office Open XML WordprocessingML Template (χωρίς μακροεντολή). |
| Dotm | `6` | Καθορίζει τη μορφή προτύπου με δυνατότητα μακροεντολής WordprocessingML του Office Open XML. |
| FlatOpc | `7` | Καθορίζει τη μορφή Office Open XML WordprocessingML που είναι αποθηκευμένη σε επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| FlatOpcMacroEnabled | `8` | Καθορίζει τη μορφή εγγράφου με δυνατότητα μακροεντολής του Office Open XML WordprocessingML που είναι αποθηκευμένο σε επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| FlatOpcTemplate | `9` | Καθορίζει τη μορφή του Office Open XML WordprocessingML Template (χωρίς μακροεντολή) που είναι αποθηκευμένη σε επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| FlatOpcTemplateMacroEnabled | `10` | Καθορίζει τη μορφή προτύπου με δυνατότητα μακροεντολής WordprocessingML του Office Open XML που είναι αποθηκευμένη σε επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| WordML | `11` | Καθορίζει τη μορφή Microsoft Word 2003 WordprocessingML. |
| Odt | `12` | Καθορίζει τη μορφή εγγράφου κειμένου ODF. |
| Ott | `13` | Καθορίζει τη μορφή προτύπου εγγράφου κειμένου ODF. |
| Xls | `14` | Καθορίζει τη μορφή δυαδικού βιβλίου εργασίας Microsoft Excel 97 - 2007. |
| Xlsx | `15` | Καθορίζει τη μορφή του Office Open XML SpreadsheetML Workbook (χωρίς μακροεντολή). |
| Xlsm | `16` | Καθορίζει τη μορφή του Office Open XML SpreadsheetML με δυνατότητα Macro-enabled βιβλίου εργασίας. |
| Xltx | `17` | Καθορίζει τη μορφή του Office Open XML SpreadsheetML Template (χωρίς μακροεντολή). |
| Xltm | `18` | Καθορίζει τη μορφή του Office Open XML SpreadsheetML με δυνατότητα Macro-Enabled Template. |
| Xlam | `19` | Καθορίζει τη μορφή του Office Open XML SpreadsheetML με δυνατότητα Macro-Enabled Add-in. |
| Xlsb | `20` | Καθορίζει τη μορφή δυαδικού αρχείου με δυνατότητα Macro-Enabled Microsoft Excel 2007. |
| SpreadsheetML | `21` | Καθορίζει τη μορφή υπολογιστικού φύλλου Microsoft Excel 2003ML. |
| Ods | `22` | Καθορίζει τη μορφή υπολογιστικού φύλλου ODF. |
| Ppt | `23` | Καθορίζει τη μορφή δυαδικής παρουσίασης Microsoft PowerPoint 97 - 2007. |
| Pps | `24` | Καθορίζει τη μορφή του Microsoft PowerPoint 97 - 2007 Binary Slide Show. |
| Pptx | `25` | Καθορίζει τη μορφή Office Open XML PresentationML Presentation (χωρίς μακροεντολή). |
| Pptm | `26` | Καθορίζει τη μορφή παρουσίασης του Office Open XML PresentationML με δυνατότητα Macro-Enabled. |
| Ppsx | `27` | Καθορίζει τη μορφή Office Open XML PresentationML Slide Show (χωρίς μακροεντολή). |
| Ppsm | `28` | Καθορίζει τη μορφή του Office Open XML PresentationML με δυνατότητα μακροεντολής παρουσίασης παρουσίασης. |
| Potx | `29` | Καθορίζει τη μορφή του Office Open XML PresentationML Template (χωρίς μακροεντολή). |
| Potm | `30` | Καθορίζει τη μορφή του Office Open XML PresentationML με δυνατότητα Macro-Enabled Template. |
| Odp | `31` | Καθορίζει τη μορφή παρουσίασης ODF. |
| MsgAscii | `32` | Καθορίζει τη μορφή του μηνύματος του Microsoft Outlook (MSG) χρησιμοποιώντας κωδικοποίηση χαρακτήρων ASCII. |
| MsgUnicode | `33` | Καθορίζει τη μορφή του μηνύματος του Microsoft Outlook (MSG) χρησιμοποιώντας κωδικοποίηση χαρακτήρων Unicode. |
| Eml | `34` | Καθορίζει την τυπική μορφή MIME. |
| Emlx | `35` | Καθορίζει τη μορφή αρχείου του προγράμματος Apple Mail.app. |
| Rtf | `36` | Καθορίζει τη μορφή RTF. |
| Text | `37` | Καθορίζει τη μορφή απλού κειμένου. |
| Xml | `38` | Καθορίζει τη μορφή XML μιας γενικής φόρμας. |
| Xaml | `39` | Καθορίζει τη μορφή επεκτάσιμης γλώσσας σήμανσης εφαρμογής (XAML). |
| XamlPackage | `40` | Καθορίζει τη μορφή πακέτου Extensible Application Markup Language (XAML). |
| Html | `41` | Καθορίζει τη μορφή HTML. |
| Mhtml | `42` | Καθορίζει τη μορφή MHTML (αρχείο Ιστού). |
| Xps | `43` | Καθορίζει τη μορφή XPS (XML Paper Specification). |
| OpenXps | `44` | Καθορίζει τη μορφή OpenXPS (Ecma-388). |
| Pdf | `45` | Καθορίζει τη μορφή PDF (Adobe Portable Document). |
| Epub | `46` | Καθορίζει τη μορφή IDPF EPUB. |
| Ps | `47` | Καθορίζει τη μορφή PS (PostScript). |
| Pcl | `48` | Καθορίζει τη μορφή PCL (Γλώσσα ελέγχου εκτυπωτή). |
| Svg | `49` | Καθορίζει τη μορφή SVG (Scalable Vector Graphics). |
| Tiff | `50` | Καθορίζει τη μορφή TIFF. |
| Markdown | `51` | Καθορίζει τη μορφή Markdown. |
| Pot | `52` | Καθορίζει τη μορφή δυαδικού προτύπου Microsoft PowerPoint 97 - 2007. |
| Otp | `53` | Καθορίζει τη μορφή του προτύπου παρουσίασης ODF. |
| Xlt | `54` | Καθορίζει τη μορφή δυαδικού προτύπου Microsoft Excel 97 - 2007. |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Assembly](../../groupdocs.assembly)
* συνέλευση [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
