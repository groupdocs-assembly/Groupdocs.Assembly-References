---
title: "تنسيق الملف"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحدد تنسيق الملف."
type: docs
weight: 30
url: /ar/net/groupdocs.assembly/fileformat/
---
## FileFormat enumeration

يحدد تنسيق الملف.

```csharp
public enum FileFormat
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Unspecified | `0` | يحدد قيمة غير مضبوطة. الافتراضية. |
| Doc | `1` | يحدد تنسيق مستند Microsoft Word 97 - 2007 الثنائي. |
| Dot | `2` | يحدد تنسيق قالب Microsoft Word 97 - 2007 الثنائي. |
| Docx | `3` | يحدد تنسيق مستند Office Open XML WordprocessingML (بدون ماكرو). |
| Docm | `4` | يحدد تنسيق مستند Office Open XML WordprocessingML مع تمكين الماكرو. |
| Dotx | `5` | يحدد تنسيق قالب Office Open XML WordprocessingML (بدون ماكرو). |
| Dotm | `6` | يحدد تنسيق قالب Office Open XML WordprocessingML مع تمكين الماكرو. |
| FlatOpc | `7` | يحدد تنسيق Office Open XML WordprocessingML المخزن في ملف XML مسطح بدلاً من حزمة ZIP. |
| FlatOpcMacroEnabled | `8` | يحدد تنسيق مستند Office Open XML WordprocessingML مع تمكين الماكرو المخزن في ملف XML مسطح بدلاً من حزمة ZIP. |
| FlatOpcTemplate | `9` | يحدد تنسيق قالب Office Open XML WordprocessingML (بدون ماكرو) المخزن في ملف XML مسطح بدلاً من حزمة ZIP. |
| FlatOpcTemplateMacroEnabled | `10` | يحدد تنسيق قالب ماكرو-مفعل Office Open XML WordprocessingML المخزن في ملف XML مسطح بدلاً من حزمة ZIP. |
| WordML | `11` | يحدد تنسيق Microsoft Word 2003 WordprocessingML. |
| Odt | `12` | يحدد تنسيق مستند نصي ODF. |
| Ott | `13` | يحدد تنسيق قالب مستند نصي ODF. |
| Xls | `14` | يحدد تنسيق دفتر عمل ثنائي Microsoft Excel 97 - 2007. |
| Xlsx | `15` | يحدد تنسيق دفتر عمل Office Open XML SpreadsheetML (بدون ماكرو). |
| Xlsm | `16` | يحدد تنسيق دفتر عمل ماكرو-مفعل Office Open XML SpreadsheetML. |
| Xltx | `17` | يحدد تنسيق قالب Office Open XML SpreadsheetML (بدون ماكرو). |
| Xltm | `18` | يحدد تنسيق قالب ماكرو-مفعل Office Open XML SpreadsheetML. |
| Xlam | `19` | يحدد تنسيق إضافة ماكرو-مفعل Office Open XML SpreadsheetML. |
| Xlsb | `20` | يحدد تنسيق ملف ثنائي ماكرو-مفعل Microsoft Excel 2007. |
| SpreadsheetML | `21` | يحدد تنسيق Microsoft Excel 2003 SpreadsheetML. |
| Ods | `22` | يحدد تنسيق جدول بيانات ODF. |
| Ppt | `23` | يحدد تنسيق عرض تقديمي ثنائي Microsoft PowerPoint 97 - 2007. |
| Pps | `24` | يحدد تنسيق عرض شرائح ثنائي Microsoft PowerPoint 97 - 2007. |
| Pptx | `25` | يحدد تنسيق عرض تقديمي Office Open XML PresentationML (بدون ماكرو). |
| Pptm | `26` | يحدد تنسيق عرض تقديمي ماكرو-مفعل Office Open XML PresentationML. |
| Ppsx | `27` | يحدد تنسيق عرض شرائح Office Open XML PresentationML (بدون ماكرو). |
| Ppsm | `28` | يحدد تنسيق عرض شرائح ماكرو-مفعل Office Open XML PresentationML. |
| Potx | `29` | يحدد تنسيق قالب Office Open XML PresentationML (بدون ماكرو). |
| Potm | `30` | يحدد تنسيق قالب ماكرو-مفعل Office Open XML PresentationML. |
| Odp | `31` | يحدد تنسيق عرض تقديمي ODF. |
| MsgAscii | `32` | يحدد تنسيق رسالة Microsoft Outlook (MSG) باستخدام ترميز أحرف ASCII. |
| MsgUnicode | `33` | يحدد تنسيق رسالة Microsoft Outlook (MSG) باستخدام ترميز أحرف Unicode. |
| Eml | `34` | يحدد تنسيق معيار MIME. |
| Emlx | `35` | يحدد تنسيق ملف برنامج Apple Mail.app. |
| Rtf | `36` | يحدد تنسيق RTF. |
| Text | `37` | يحدد تنسيق النص العادي. |
| Xml | `38` | يحدد تنسيق XML لنموذج عام. |
| Xaml | `39` | يحدد تنسيق لغة توصيف التطبيقات القابلة للتوسيع (XAML). |
| XamlPackage | `40` | يحدد تنسيق حزمة لغة توصيف التطبيقات القابلة للتوسيع (XAML). |
| Html | `41` | يحدد تنسيق HTML. |
| Mhtml | `42` | يحدد تنسيق MHTML (أرشيف الويب). |
| Xps | `43` | يحدد تنسيق XPS (مواصفة الورق XML). |
| OpenXps | `44` | يحدد تنسيق OpenXPS (Ecma-388). |
| Pdf | `45` | يحدد تنسيق PDF (مستند Adobe المحمول). |
| Epub | `46` | يحدد تنسيق IDPF EPUB. |
| Ps | `47` | يحدد تنسيق PS (PostScript). |
| Pcl | `48` | يحدد تنسيق PCL (لغة التحكم بالطابعة). |
| Svg | `49` | يحدد تنسيق SVG (رسومات متجهية قابلة للتوسع). |
| Tiff | `50` | يحدد تنسيق TIFF. |
| Markdown | `51` | يحدد تنسيق Markdown. |
| Pot | `52` | يحدد تنسيق قالب Microsoft PowerPoint الثنائي 97 - 2007. |
| Otp | `53` | يحدد تنسيق قالب عرض ODF. |
| Xlt | `54` | يحدد تنسيق قالب Microsoft Excel الثنائي 97 - 2007. |

### انظر أيضًا

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
