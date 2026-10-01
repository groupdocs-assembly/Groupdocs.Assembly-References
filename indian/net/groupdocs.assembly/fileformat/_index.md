---
title: "FileFormat"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "फ़ाइल के फ़ॉर्मैट को निर्दिष्ट करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.assembly/fileformat/
---
## FileFormat enumeration

फ़ाइल के फ़ॉर्मैट को निर्दिष्ट करता है।

```csharp
public enum FileFormat
```

### Values

| नाम | Value | विवरण |
| --- | --- | --- |
| Unspecified | `0` | एक अनसेट मान निर्दिष्ट करता है। डिफ़ॉल्ट। |
| Doc | `1` | Microsoft Word 97 - 2007 बाइनरी डॉक्यूमेंट फ़ॉर्मेट निर्दिष्ट करता है। |
| Dot | `2` | Microsoft Word 97 - 2007 बाइनरी टेम्प्लेट फ़ॉर्मेट निर्दिष्ट करता है। |
| Docx | `3` | Office Open XML WordprocessingML डॉक्यूमेंट (मैक्रो-फ़्री) फ़ॉर्मेट निर्दिष्ट करता है। |
| Docm | `4` | Office Open XML WordprocessingML मैक्रो-एनेबल्ड डॉक्यूमेंट फ़ॉर्मेट निर्दिष्ट करता है। |
| Dotx | `5` | Office Open XML WordprocessingML टेम्प्लेट (मैक्रो-फ़्री) फ़ॉर्मेट निर्दिष्ट करता है। |
| Dotm | `6` | Office Open XML WordprocessingML मैक्रो-एनेबल्ड टेम्प्लेट फ़ॉर्मेट निर्दिष्ट करता है। |
| FlatOpc | `7` | ZIP पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत Office Open XML WordprocessingML फ़ॉर्मेट निर्दिष्ट करता है। |
| FlatOpcMacroEnabled | `8` | ZIP पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत Office Open XML WordprocessingML मैक्रो-एनेबल्ड डॉक्यूमेंट फ़ॉर्मेट निर्दिष्ट करता है। |
| FlatOpcTemplate | `9` | ZIP पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत Office Open XML WordprocessingML टेम्प्लेट (मैक्रो-फ़्री) फ़ॉर्मेट निर्दिष्ट करता है। |
| FlatOpcTemplateMacroEnabled | `10` | Office Open XML WordprocessingML Macro-Enabled Template फ़ॉर्मेट को एक फ्लैट XML फ़ाइल में संग्रहीत, ZIP पैकेज के बजाय, निर्दिष्ट करता है। |
| WordML | `11` | Microsoft Word 2003 WordprocessingML फ़ॉर्मेट को निर्दिष्ट करता है। |
| Odt | `12` | ODF Text Document फ़ॉर्मेट को निर्दिष्ट करता है। |
| Ott | `13` | ODF Text Document Template फ़ॉर्मेट को निर्दिष्ट करता है। |
| Xls | `14` | Microsoft Excel 97 - 2007 Binary Workbook फ़ॉर्मेट को निर्दिष्ट करता है। |
| Xlsx | `15` | Office Open XML SpreadsheetML Workbook (macro-free) फ़ॉर्मेट को निर्दिष्ट करता है। |
| Xlsm | `16` | Office Open XML SpreadsheetML Macro-Enabled Workbook फ़ॉर्मेट को निर्दिष्ट करता है। |
| Xltx | `17` | Office Open XML SpreadsheetML Template (macro-free) फ़ॉर्मेट को निर्दिष्ट करता है। |
| Xltm | `18` | Office Open XML SpreadsheetML Macro-Enabled Template फ़ॉर्मेट को निर्दिष्ट करता है। |
| Xlam | `19` | Office Open XML SpreadsheetML Macro-Enabled Add-in फ़ॉर्मेट को निर्दिष्ट करता है। |
| Xlsb | `20` | Microsoft Excel 2007 Macro-Enabled Binary File फ़ॉर्मेट को निर्दिष्ट करता है। |
| SpreadsheetML | `21` | Microsoft Excel 2003 SpreadsheetML फ़ॉर्मेट को निर्दिष्ट करता है। |
| Ods | `22` | ODF Spreadsheet फ़ॉर्मेट को निर्दिष्ट करता है। |
| Ppt | `23` | Microsoft PowerPoint 97 - 2007 Binary Presentation फ़ॉर्मेट को निर्दिष्ट करता है। |
| Pps | `24` | Microsoft PowerPoint 97 - 2007 Binary Slide Show फ़ॉर्मेट को निर्दिष्ट करता है। |
| Pptx | `25` | Office Open XML PresentationML Presentation (macro-free) फ़ॉर्मेट को निर्दिष्ट करता है। |
| Pptm | `26` | Office Open XML PresentationML Macro-Enabled Presentation फ़ॉर्मेट को निर्दिष्ट करता है। |
| Ppsx | `27` | Office Open XML PresentationML Slide Show (macro-free) फ़ॉर्मेट को निर्दिष्ट करता है। |
| Ppsm | `28` | Office Open XML PresentationML Macro-Enabled Slide Show फ़ॉर्मेट को निर्दिष्ट करता है। |
| Potx | `29` | Office Open XML PresentationML Template (macro-free) फ़ॉर्मेट को निर्दिष्ट करता है। |
| Potm | `30` | Office Open XML PresentationML Macro-Enabled Template फ़ॉर्मेट को निर्दिष्ट करता है। |
| Odp | `31` | ODF Presentation फ़ॉर्मेट को निर्दिष्ट करता है। |
| MsgAscii | `32` | ASCII कैरेक्टर एन्कोडिंग का उपयोग करके Microsoft Outlook Message (MSG) फ़ॉर्मेट को निर्दिष्ट करता है। |
| MsgUnicode | `33` | Unicode कैरेक्टर एन्कोडिंग का उपयोग करके Microsoft Outlook Message (MSG) फ़ॉर्मेट को निर्दिष्ट करता है। |
| Eml | `34` | MIME मानक फ़ॉर्मेट को निर्दिष्ट करता है। |
| Emlx | `35` | Apple Mail.app प्रोग्राम फ़ाइल स्वरूप को निर्दिष्ट करता है। |
| Rtf | `36` | RTF स्वरूप को निर्दिष्ट करता है। |
| Text | `37` | सादा पाठ स्वरूप को निर्दिष्ट करता है। |
| Xml | `38` | सामान्य फ़ॉर्म का XML स्वरूप को निर्दिष्ट करता है। |
| Xaml | `39` | Extensible Application Markup Language (XAML) स्वरूप को निर्दिष्ट करता है। |
| XamlPackage | `40` | Extensible Application Markup Language (XAML) पैकेज स्वरूप को निर्दिष्ट करता है। |
| Html | `41` | HTML स्वरूप को निर्दिष्ट करता है। |
| Mhtml | `42` | MHTML (वेब अभिलेख) स्वरूप को निर्दिष्ट करता है। |
| Xps | `43` | XPS (XML पेपर स्पेसिफिकेशन) स्वरूप को निर्दिष्ट करता है। |
| OpenXps | `44` | OpenXPS (Ecma-388) स्वरूप को निर्दिष्ट करता है। |
| Pdf | `45` | PDF (Adobe पोर्टेबल डॉक्यूमेंट) स्वरूप को निर्दिष्ट करता है। |
| Epub | `46` | IDPF EPUB स्वरूप को निर्दिष्ट करता है। |
| Ps | `47` | PS (PostScript) स्वरूप को निर्दिष्ट करता है। |
| Pcl | `48` | PCL (Printer Control Language) स्वरूप को निर्दिष्ट करता है। |
| Svg | `49` | SVG (Scalable Vector Graphics) स्वरूप को निर्दिष्ट करता है। |
| Tiff | `50` | TIFF स्वरूप को निर्दिष्ट करता है। |
| Markdown | `51` | Markdown स्वरूप को निर्दिष्ट करता है। |
| Pot | `52` | Microsoft PowerPoint 97 - 2007 बाइनरी टेम्प्लेट स्वरूप को निर्दिष्ट करता है। |
| Otp | `53` | ODF प्रेजेंटेशन टेम्प्लेट स्वरूप को निर्दिष्ट करता है। |
| Xlt | `54` | Microsoft Excel 97 - 2007 बाइनरी टेम्प्लेट स्वरूप को निर्दिष्ट करता है। |

### संबंधित देखें

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
