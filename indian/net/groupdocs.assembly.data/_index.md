---
title: "GroupDocs.Assembly.Data"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "दस्तावेज़ को असेंबल करते समय उपयोग किए जाने वाले बाहरी दस्तावेज़ों के डेटा तक पहुँचने के लिए क्लास प्रदान करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.assembly.data/
---
दस्तावेज़ को असेंबल करते समय उपयोग किए जाने वाले बाहरी दस्तावेज़ों के डेटा तक पहुँचने के लिए क्लास प्रदान करता है।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | CSV डेटा को पार्स करने के विकल्पों का प्रतिनिधित्व करता है। |
| [CsvDataSource](./csvdatasource) | दस्तावेज़ को असेंबल करते समय उपयोग के लिए CSV फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है। |
| [DocumentTable](./documenttable) | बाहरी दस्तावेज़ में स्थित एकल तालिका (या स्प्रेडशीट) के डेटा तक पहुँच प्रदान करता है, जिसे दस्तावेज़ को असेंबल करते समय उपयोग किया जाता है। |
| [DocumentTableCollection](./documenttablecollection) | किसी विशिष्ट [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) उदाहरण की [`DocumentTable`](../groupdocs.assembly.data/documenttable) वस्तुओं का केवल-पढ़ने योग्य संग्रह दर्शाता है। |
| [DocumentTableColumn](./documenttablecolumn) | किसी विशिष्ट [`DocumentTable`](../groupdocs.assembly.data/documenttable) वस्तु का एकल स्तंभ दर्शाता है। |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | किसी विशिष्ट [`DocumentTable`](../groupdocs.assembly.data/documenttable) उदाहरण की [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) वस्तुओं का केवल-पढ़ने योग्य संग्रह दर्शाता है। |
| [DocumentTableLoadArgs](./documenttableloadargs) | [`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle) विधि के लिए डेटा प्रदान करता है। |
| [DocumentTableOptions](./documenttableoptions) | दस्तावेज़ तालिका से डेटा निष्कर्षण को नियंत्रित करने के लिए विकल्पों का एक सेट प्रदान करता है। |
| [DocumentTableRelation](./documenttablerelation) | दो [`DocumentTable`](../groupdocs.assembly.data/documenttable) वस्तुओं के बीच एक पैरेंट-चाइल्ड संबंध दर्शाता है। |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | एकल [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) उदाहरण की [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) वस्तुओं का संग्रह दर्शाता है। |
| [DocumentTableSet](./documenttableset) | बाहरी दस्तावेज़ में स्थित कई तालिकाओं (या स्प्रेडशीट) के डेटा तक पहुँच प्रदान करता है, जिसे दस्तावेज़ को असेंबल करते समय उपयोग किया जाता है। साथ ही, दस्तावेज़ तालिकाओं के लिए पैरेंट-चाइल्ड संबंध निर्धारित करने की सुविधा देता है, जिससे टेम्पलेट दस्तावेज़ों में संबंधित डेटा तक पहुँच सरल हो जाती है। |
| [JsonDataLoadOptions](./jsondataloadoptions) | JSON डेटा पार्स करने के विकल्प दर्शाता है। |
| [JsonDataSource](./jsondatasource) | दस्तावेज़ को असेंबल करते समय उपयोग के लिए JSON फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है। |
| [XmlDataLoadOptions](./xmldataloadoptions) | XML डेटा लोड करने के विकल्प दर्शाता है। |
| [XmlDataSource](./xmldatasource) | दस्तावेज़ को असेंबल करते समय उपयोग के लिए XML फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है। |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | [`DocumentTable`](../groupdocs.assembly.data/documenttable) वस्तुओं के डिफ़ॉल्ट लोडिंग को ओवरराइड करता है जबकि एक [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) उदाहरण बनाया जा रहा है। |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | JSON लोड करते समय JSON सरल मानों (null, boolean, number, integer, और string) को पार्स करने के लिए एक मोड निर्दिष्ट करता है। ऐसा मोड दिनांक-समय मानों के पार्सिंग को प्रभावित नहीं करता। |

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
