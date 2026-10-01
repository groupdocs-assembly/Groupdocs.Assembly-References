---
title: "DocumentTableColumnCollection"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "एक पढ़ने-के-लिए-केवल संग्रह का प्रतिनिधित्व करता है जो किसी विशेष DocumentTable./documenttable उदाहरण के DocumentTableColumn./documenttablecolumn वस्तुओं का होता है।"
type: docs
weight: 150
url: /hi/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

एक पढ़ने-के-लिए-केवल संग्रह का प्रतिनिधित्व करता है जो किसी विशेष [`DocumentTable`](../documenttable) उदाहरण के [`DocumentTableColumn`](../documenttablecolumn) वस्तुओं का होता है।

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | संग्रह में मौजूद [`DocumentTableColumn`](../documenttablecolumn) वस्तुओं की कुल संख्या प्राप्त करता है। |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | निर्दिष्ट अनुक्रमांक पर संग्रह से एक [`DocumentTableColumn`](../documenttablecolumn) उदाहरण प्राप्त करता है। (2 इंडेक्सर) |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | एक मान लौटाता है जो दर्शाता है कि क्या यह संग्रह निर्दिष्ट कॉलम को शामिल करता है। |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | एक मान लौटाता है जो दर्शाता है कि क्या यह संग्रह निर्दिष्ट नाम वाले कॉलम को शामिल करता है। |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | इस संग्रह के [`DocumentTableColumn`](../documenttablecolumn) वस्तुओं पर पुनरावृत्ति करने के लिए एक इटेरेटर लौटाता है। |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | इस संग्रह में निर्दिष्ट कॉलम का अनुक्रमांक लौटाता है। |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | इस संग्रह में निर्दिष्ट नाम वाले कॉलम का अनुक्रमांक लौटाता है। |

### टिप्पणियाँ

संग्रह को दस्तावेज़ से संबंधित तालिका लोड करते समय स्वचालित रूप से भरा जाता है और इसे संशोधित नहीं किया जा सकता। हालांकि, संग्रह में शामिल [`DocumentTableColumn`](../documenttablecolumn) वस्तुओं की गुणधर्मों को संशोधित किया जा सकता है।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
