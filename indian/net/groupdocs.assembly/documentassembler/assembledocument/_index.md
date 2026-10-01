---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "निर्दिष्ट स्रोत पथ से एक टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है और डिफ़ॉल्ट LoadSaveOptionsgroupdocs.assembly/loadsaveoptions का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य पथ पर सहेजता है।"
type: docs
weight: 50
url: /hi/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

निर्दिष्ट स्रोत पथ से एक टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और डिफ़ॉल्ट [`LoadSaveOptions`](../../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य पथ पर सहेजता है।

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourcePath | String | डेटा से भरने के लिए टेम्पलेट दस्तावेज़ का पथ। |
| targetPath | String | परिणाम दस्तावेज़ का पथ। |
| dataSourceInfos | DataSourceInfo[] | उपयोग किए जाने वाले डेटा स्रोत वस्तुओं की जानकारी प्रदान करता है। |

### रिटर्न वैल्यू

एक फ़्लैग जो दर्शाता है कि टेम्पलेट दस्तावेज़ का पार्सिंग सफल रहा या नहीं। लौटाया गया फ़्लैग केवल तभी अर्थपूर्ण होता है जब [`Options`](../options) प्रॉपर्टी का मान InlineErrorMessages विकल्प को शामिल करता हो।

### संबंधित देखें

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

निर्दिष्ट स्रोत पथ से एक टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और दिए गए [`LoadSaveOptions`](../../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य पथ पर सहेजता है।

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourcePath | String | डेटा से भरने के लिए टेम्पलेट दस्तावेज़ का पथ। |
| targetPath | String | परिणाम दस्तावेज़ का पथ। |
| loadSaveOptions | LoadSaveOptions | दस्तावेज़ लोडिंग और सहेजने के लिए अतिरिक्त विकल्प निर्दिष्ट करता है। |
| dataSourceInfos | DataSourceInfo[] | उपयोग किए जाने वाले डेटा स्रोत वस्तुओं की जानकारी प्रदान करता है। |

### रिटर्न वैल्यू

एक फ़्लैग जो दर्शाता है कि टेम्पलेट दस्तावेज़ का पार्सिंग सफल रहा या नहीं। लौटाया गया फ़्लैग केवल तभी अर्थपूर्ण होता है जब [`Options`](../options) प्रॉपर्टी का मान InlineErrorMessages विकल्प को शामिल करता हो।

### संबंधित देखें

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

निर्दिष्ट स्रोत स्ट्रीम से एक टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और डिफ़ॉल्ट [`LoadSaveOptions`](../../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य स्ट्रीम पर सहेजता है।

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStream | Stream | टेम्पलेट दस्तावेज़ पढ़ने के लिए स्ट्रीम। |
| targetStream | Stream | परिणाम दस्तावेज़ लिखने के लिए स्ट्रीम। |
| dataSourceInfos | DataSourceInfo[] | उपयोग किए जाने वाले डेटा स्रोत वस्तुओं की जानकारी प्रदान करता है। |

### रिटर्न वैल्यू

एक फ़्लैग जो दर्शाता है कि टेम्पलेट दस्तावेज़ का पार्सिंग सफल रहा या नहीं। लौटाया गया फ़्लैग केवल तभी अर्थपूर्ण होता है जब [`Options`](../options) प्रॉपर्टी का मान InlineErrorMessages विकल्प को शामिल करता हो।

### संबंधित देखें

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

निर्दिष्ट स्रोत स्ट्रीम से एक टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और दिए गए [`LoadSaveOptions`](../../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य स्ट्रीम पर सहेजता है।

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStream | Stream | टेम्पलेट दस्तावेज़ पढ़ने के लिए स्ट्रीम। |
| targetStream | Stream | परिणाम दस्तावेज़ लिखने के लिए स्ट्रीम। |
| loadSaveOptions | LoadSaveOptions | दस्तावेज़ लोडिंग और सहेजने के लिए अतिरिक्त विकल्प निर्दिष्ट करता है। |
| dataSourceInfos | DataSourceInfo[] | उपयोग किए जाने वाले डेटा स्रोत वस्तुओं की जानकारी प्रदान करता है। |

### रिटर्न वैल्यू

एक फ़्लैग जो दर्शाता है कि टेम्पलेट दस्तावेज़ का पार्सिंग सफल रहा या नहीं। लौटाया गया फ़्लैग केवल तभी अर्थपूर्ण होता है जब [`Options`](../options) प्रॉपर्टी का मान InlineErrorMessages विकल्प को शामिल करता हो।

### संबंधित देखें

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
