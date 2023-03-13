---
title: AssembleDocument
second_title: GroupDocs.Assembly .NET API संदर्भ के लिए
description: नर्दष्ट स्रत पथ से एक टेम्पलेट दस्तवेज़ लड करत है टेम्पलेट दस्तवेज़ क नर्दष्ट एकल य एकधक स्रतं से डेट के सथ पप्युलेट करत है और परणम दस्तवेज़ क डफ़ल्ट क उपयग करके लक्ष्य पथ पर संग्रहत करत हैLoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /hi/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

निर्दिष्ट स्रोत पथ से एक टेम्पलेट दस्तावेज़ लोड करता है, टेम्पलेट दस्तावेज़ को निर्दिष्ट एकल या एकाधिक स्रोतों से डेटा के साथ पॉप्युलेट करता है, और परिणाम दस्तावेज़ को डिफ़ॉल्ट का उपयोग करके लक्ष्य पथ पर संग्रहीत करता है[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourcePath | String | डेटा के साथ पॉप्युलेट किए जाने वाले टेम्प्लेट दस्तावेज़ का पथ। |
| targetPath | String | परिणाम दस्तावेज़ का पथ। |
| dataSourceInfos | DataSourceInfo[] | उपयोग की जाने वाली डेटा स्रोत वस्तुओं के बारे में जानकारी प्रदान करता है। |

### प्रतिलाभ की मात्रा

एक ध्वज इंगित करता है कि टेम्पलेट दस्तावेज़ का विश्लेषण सफल रहा था या नहीं। लौटा हुआ झंडा केवल तभी समझ में आता है जब का मान हो[`Options`](../options) संपत्ति में शामिल हैInlineErrorMessages विकल्प.

### यह सभी देखें

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* नाम स्थान [GroupDocs.Assembly](../../documentassembler)
* सभा [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

निर्दिष्ट स्रोत पथ से एक टेम्पलेट दस्तावेज़ लोड करता है, टेम्पलेट दस्तावेज़ को निर्दिष्ट एकल या एकाधिक स्रोतों से डेटा के साथ पॉप्युलेट करता है, और परिणाम दस्तावेज़ को दिए गए का उपयोग करके लक्ष्य पथ पर संग्रहीत करता है[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourcePath | String | डेटा के साथ पॉप्युलेट किए जाने वाले टेम्प्लेट दस्तावेज़ का पथ। |
| targetPath | String | परिणाम दस्तावेज़ का पथ। |
| loadSaveOptions | LoadSaveOptions | दस्तावेज़ लोड करने और सहेजने के लिए अतिरिक्त विकल्प निर्दिष्ट करता है। |
| dataSourceInfos | DataSourceInfo[] | उपयोग की जाने वाली डेटा स्रोत वस्तुओं के बारे में जानकारी प्रदान करता है। |

### प्रतिलाभ की मात्रा

एक ध्वज इंगित करता है कि टेम्पलेट दस्तावेज़ का विश्लेषण सफल रहा था या नहीं। लौटा हुआ झंडा केवल तभी समझ में आता है जब का मान हो[`Options`](../options) संपत्ति में शामिल हैInlineErrorMessages विकल्प.

### यह सभी देखें

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* नाम स्थान [GroupDocs.Assembly](../../documentassembler)
* सभा [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

निर्दिष्ट स्रोत स्ट्रीम से एक टेम्पलेट दस्तावेज़ लोड करता है, टेम्पलेट दस्तावेज़ को निर्दिष्ट एकल या एकाधिक स्रोतों से डेटा के साथ पॉप्युलेट करता है, और परिणाम दस्तावेज़ को डिफ़ॉल्ट का उपयोग करके लक्ष्य स्ट्रीम में संग्रहीत करता है[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStream | Stream | वह स्ट्रीम जिससे टेम्प्लेट दस्तावेज़ पढ़ा जाना है. |
| targetStream | Stream | परिणाम दस्तावेज़ लिखने के लिए धारा। |
| dataSourceInfos | DataSourceInfo[] | उपयोग की जाने वाली डेटा स्रोत वस्तुओं के बारे में जानकारी प्रदान करता है। |

### प्रतिलाभ की मात्रा

एक ध्वज इंगित करता है कि टेम्पलेट दस्तावेज़ का विश्लेषण सफल रहा था या नहीं। लौटा हुआ झंडा केवल तभी समझ में आता है जब का मान हो[`Options`](../options) संपत्ति में शामिल हैInlineErrorMessages विकल्प.

### यह सभी देखें

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* नाम स्थान [GroupDocs.Assembly](../../documentassembler)
* सभा [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

निर्दिष्ट स्रोत स्ट्रीम से एक टेम्पलेट दस्तावेज़ लोड करता है, टेम्पलेट दस्तावेज़ को निर्दिष्ट एकल या एकाधिक स्रोतों से डेटा के साथ पॉप्युलेट करता है, और परिणाम दस्तावेज़ को दिए गए का उपयोग करके लक्ष्य स्ट्रीम में संग्रहीत करता है[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStream | Stream | वह स्ट्रीम जिससे टेम्प्लेट दस्तावेज़ पढ़ा जाना है. |
| targetStream | Stream | परिणाम दस्तावेज़ लिखने के लिए धारा। |
| loadSaveOptions | LoadSaveOptions | दस्तावेज़ लोड करने और सहेजने के लिए अतिरिक्त विकल्प निर्दिष्ट करता है। |
| dataSourceInfos | DataSourceInfo[] | उपयोग की जाने वाली डेटा स्रोत वस्तुओं के बारे में जानकारी प्रदान करता है। |

### प्रतिलाभ की मात्रा

एक ध्वज इंगित करता है कि टेम्पलेट दस्तावेज़ का विश्लेषण सफल रहा था या नहीं। लौटा हुआ झंडा केवल तभी समझ में आता है जब का मान हो[`Options`](../options) संपत्ति में शामिल हैInlineErrorMessages विकल्प.

### यह सभी देखें

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* नाम स्थान [GroupDocs.Assembly](../../documentassembler)
* सभा [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
