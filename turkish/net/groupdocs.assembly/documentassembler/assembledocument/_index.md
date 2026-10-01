---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Belirtilen kaynak yoldan bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef yola, varsayılan LoadSaveOptionsgroupdocs.assembly/loadsaveoptions kullanarak kaydeder."
type: docs
weight: 50
url: /tr/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Belirtilen kaynak yoldan bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef yola, varsayılan [`LoadSaveOptions`](../../loadsaveoptions) kullanarak kaydeder.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourcePath | String | Veri ile doldurulacak şablon belgesinin yolu. |
| targetPath | String | Sonuç belgesinin yolu. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Dönüş Değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak yalnızca [`Options`](../options) özelliğinin değeri InlineErrorMessages seçeneğini içeriyorsa anlamlıdır.

### Ayrıca Bakınız

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Belirtilen kaynak yoldan bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef yola, verilen [`LoadSaveOptions`](../../loadsaveoptions) kullanarak kaydeder.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourcePath | String | Veri ile doldurulacak şablon belgesinin yolu. |
| targetPath | String | Sonuç belgesinin yolu. |
| loadSaveOptions | LoadSaveOptions | Belge yükleme ve kaydetme için ek seçenekler belirtir. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Dönüş Değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak yalnızca [`Options`](../options) özelliğinin değeri InlineErrorMessages seçeneğini içeriyorsa anlamlıdır.

### Ayrıca Bakınız

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Belirtilen kaynak akışından bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef akışa, varsayılan [`LoadSaveOptions`](../../loadsaveoptions) kullanarak kaydeder.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStream | Stream | Şablon belgesini okumak için kullanılan akış. |
| targetStream | Stream | Sonuç belgesini yazmak için kullanılan akış. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Dönüş Değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak yalnızca [`Options`](../options) özelliğinin değeri InlineErrorMessages seçeneğini içeriyorsa anlamlıdır.

### Ayrıca Bakınız

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Belirtilen kaynak akışından bir şablon belgesi yükler, şablon belgesini belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonucu hedef akışa, verilen [`LoadSaveOptions`](../../loadsaveoptions) kullanarak kaydeder.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStream | Stream | Şablon belgesini okumak için kullanılan akış. |
| targetStream | Stream | Sonuç belgesini yazmak için kullanılan akış. |
| loadSaveOptions | LoadSaveOptions | Belge yükleme ve kaydetme için ek seçenekler belirtir. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Dönüş Değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak yalnızca [`Options`](../options) özelliğinin değeri InlineErrorMessages seçeneğini içeriyorsa anlamlıdır.

### Ayrıca Bakınız

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
