---
title: "AssembleDocument"
second_title: "Referensi API GroupDocs.Assembly untuk .NET"
description: "Memuat dokumen templat dari jalur sumber yang ditentukan, mengisi dokumen templat dengan data dari satu atau beberapa sumber yang ditentukan, dan menyimpan dokumen hasil ke jalur target menggunakan default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /id/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Memuat dokumen templat dari jalur sumber yang ditentukan, mengisi dokumen templat dengan data dari satu atau beberapa sumber yang ditentukan, dan menyimpan dokumen hasil ke jalur target menggunakan default [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur ke dokumen templat yang akan diisi dengan data. |
| targetPath | String | Jalur ke dokumen hasil. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Kembali

Bendera yang menunjukkan apakah parsing dokumen templat berhasil. Bendera yang dikembalikan hanya masuk akal jika nilai properti [`Options`](../options) mencakup opsi InlineErrorMessages.

### Lihat Juga

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Memuat dokumen templat dari jalur sumber yang ditentukan, mengisi dokumen templat dengan data dari satu atau beberapa sumber yang ditentukan, dan menyimpan dokumen hasil ke jalur target menggunakan [`LoadSaveOptions`](../../loadsaveoptions) yang diberikan.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur ke dokumen templat yang akan diisi dengan data. |
| targetPath | String | Jalur ke dokumen hasil. |
| loadSaveOptions | LoadSaveOptions | Menentukan opsi tambahan untuk pemuatan dan penyimpanan dokumen. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Kembali

Bendera yang menunjukkan apakah parsing dokumen templat berhasil. Bendera yang dikembalikan hanya masuk akal jika nilai properti [`Options`](../options) mencakup opsi InlineErrorMessages.

### Lihat Juga

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Memuat dokumen templat dari aliran sumber yang ditentukan, mengisi dokumen templat dengan data dari satu atau beberapa sumber yang ditentukan, dan menyimpan dokumen hasil ke aliran target menggunakan default [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| sourceStream | Stream | Aliran untuk membaca dokumen templat. |
| targetStream | Stream | Aliran untuk menulis dokumen hasil. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Kembali

Bendera yang menunjukkan apakah parsing dokumen templat berhasil. Bendera yang dikembalikan hanya masuk akal jika nilai properti [`Options`](../options) mencakup opsi InlineErrorMessages.

### Lihat Juga

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Memuat dokumen templat dari aliran sumber yang ditentukan, mengisi dokumen templat dengan data dari satu atau beberapa sumber yang ditentukan, dan menyimpan dokumen hasil ke aliran target menggunakan [`LoadSaveOptions`](../../loadsaveoptions) yang diberikan.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| sourceStream | Stream | Aliran untuk membaca dokumen templat. |
| targetStream | Stream | Aliran untuk menulis dokumen hasil. |
| loadSaveOptions | LoadSaveOptions | Menentukan opsi tambahan untuk pemuatan dan penyimpanan dokumen. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Kembali

Bendera yang menunjukkan apakah parsing dokumen templat berhasil. Bendera yang dikembalikan hanya masuk akal jika nilai properti [`Options`](../options) mencakup opsi InlineErrorMessages.

### Lihat Juga

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
