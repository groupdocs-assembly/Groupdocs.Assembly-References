---
title: AssembleDocument
second_title: .NET API Başvurusu için GroupDocs.Assembly
description: Belirtilen kaynak yoldan bir şablon belge yükler şablon belgeyi belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonuç belgesini default kullanarak hedef yola depolarLoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /tr/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Belirtilen kaynak yoldan bir şablon belge yükler, şablon belgeyi belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonuç belgesini default kullanarak hedef yola depolar[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sourcePath | String | Verilerle doldurulacak bir şablon belgesinin yolu. |
| targetPath | String | Bir sonuç belgesinin yolu. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Geri dönüş değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak, yalnızca şu değerin bir değeri ise anlamlıdır:[`Options`](../options) mülkiyet içerirInlineErrorMessages seçeneği.

### Ayrıca bakınız

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ad alanı [GroupDocs.Assembly](../../documentassembler)
* toplantı [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Belirtilen kaynak yoldan bir şablon belge yükler, şablon belgeyi belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonuç belgesini verili kullanarak hedef yola depolar[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sourcePath | String | Verilerle doldurulacak bir şablon belgesinin yolu. |
| targetPath | String | Bir sonuç belgesinin yolu. |
| loadSaveOptions | LoadSaveOptions | Belge yükleme ve kaydetme için ek seçenekleri belirtir. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Geri dönüş değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak, yalnızca şu değerin bir değeri ise anlamlıdır:[`Options`](../options) mülkiyet içerirInlineErrorMessages seçeneği.

### Ayrıca bakınız

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ad alanı [GroupDocs.Assembly](../../documentassembler)
* toplantı [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Belirtilen kaynak akıştan bir şablon belge yükler, şablon belgeyi belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonuç belgesini default kullanarak hedef akışa depolar[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sourceStream | Stream | Bir şablon belgesinin okunacağı akış. |
| targetStream | Stream | Bir sonuç belgesi yazmak için akış. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Geri dönüş değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak, yalnızca şu değerin bir değeri ise anlamlıdır:[`Options`](../options) mülkiyet içerirInlineErrorMessages seçeneği.

### Ayrıca bakınız

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ad alanı [GroupDocs.Assembly](../../documentassembler)
* toplantı [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Belirtilen kaynak akıştan bir şablon belge yükler, şablon belgeyi belirtilen tek veya birden çok kaynaktan gelen verilerle doldurur ve sonuç belgesini verili kullanarak hedef akışa depolar[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sourceStream | Stream | Bir şablon belgesinin okunacağı akış. |
| targetStream | Stream | Bir sonuç belgesi yazmak için akış. |
| loadSaveOptions | LoadSaveOptions | Belge yükleme ve kaydetme için ek seçenekleri belirtir. |
| dataSourceInfos | DataSourceInfo[] | Kullanılacak veri kaynağı nesneleri hakkında bilgi sağlar. |

### Geri dönüş değeri

Şablon belgesinin ayrıştırılmasının başarılı olup olmadığını gösteren bir bayrak. Döndürülen bayrak, yalnızca şu değerin bir değeri ise anlamlıdır:[`Options`](../options) mülkiyet içerirInlineErrorMessages seçeneği.

### Ayrıca bakınız

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ad alanı [GroupDocs.Assembly](../../documentassembler)
* toplantı [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
