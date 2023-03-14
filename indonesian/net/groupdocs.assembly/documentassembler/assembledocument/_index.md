---
title: AssembleDocument
second_title: GroupDocs.Assembly untuk Referensi .NET API
description: Memuat dokumen template dari jalur sumber yang ditentukan mengisi dokumen template dengan data dari sumber tunggal atau ganda yang ditentukan dan menyimpan dokumen hasil ke jalur target menggunakan default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /id/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Memuat dokumen template dari jalur sumber yang ditentukan, mengisi dokumen template dengan data dari sumber tunggal atau ganda yang ditentukan, dan menyimpan dokumen hasil ke jalur target menggunakan default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| sourcePath | String | Jalur ke dokumen template yang akan diisi dengan data. |
| targetPath | String | Jalur ke dokumen hasil. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Pengembalian

Bendera yang menunjukkan apakah penguraian dokumen template berhasil. Bendera yang dikembalikan masuk akal hanya jika nilai dari[`Options`](../options) properti termasukInlineErrorMessages opsi.

### Lihat juga

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ruang nama [GroupDocs.Assembly](../../documentassembler)
* perakitan [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Memuat dokumen template dari jalur sumber yang ditentukan, mengisi dokumen template dengan data dari sumber tunggal atau ganda yang ditentukan, dan menyimpan dokumen hasil ke jalur target menggunakan diberikan [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| sourcePath | String | Jalur ke dokumen template yang akan diisi dengan data. |
| targetPath | String | Jalur ke dokumen hasil. |
| loadSaveOptions | LoadSaveOptions | Menentukan opsi tambahan untuk memuat dan menyimpan dokumen. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Pengembalian

Bendera yang menunjukkan apakah penguraian dokumen template berhasil. Bendera yang dikembalikan masuk akal hanya jika nilai dari[`Options`](../options) properti termasukInlineErrorMessages opsi.

### Lihat juga

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ruang nama [GroupDocs.Assembly](../../documentassembler)
* perakitan [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Memuat dokumen template dari aliran sumber yang ditentukan, mengisi dokumen template dengan data dari sumber tunggal atau ganda yang ditentukan, dan menyimpan dokumen hasil ke aliran target menggunakan default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| sourceStream | Stream | Aliran untuk membaca dokumen template dari. |
| targetStream | Stream | Aliran untuk menulis dokumen hasil. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Pengembalian

Bendera yang menunjukkan apakah penguraian dokumen template berhasil. Bendera yang dikembalikan masuk akal hanya jika nilai dari[`Options`](../options) properti termasukInlineErrorMessages opsi.

### Lihat juga

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ruang nama [GroupDocs.Assembly](../../documentassembler)
* perakitan [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Memuat dokumen template dari aliran sumber yang ditentukan, mengisi dokumen template dengan data dari sumber tunggal atau ganda yang ditentukan, dan menyimpan dokumen hasil ke aliran target menggunakan diberikan [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| sourceStream | Stream | Aliran untuk membaca dokumen template dari. |
| targetStream | Stream | Aliran untuk menulis dokumen hasil. |
| loadSaveOptions | LoadSaveOptions | Menentukan opsi tambahan untuk memuat dan menyimpan dokumen. |
| dataSourceInfos | DataSourceInfo[] | Memberikan informasi tentang objek sumber data yang akan digunakan. |

### Nilai Pengembalian

Bendera yang menunjukkan apakah penguraian dokumen template berhasil. Bendera yang dikembalikan masuk akal hanya jika nilai dari[`Options`](../options) properti termasukInlineErrorMessages opsi.

### Lihat juga

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* ruang nama [GroupDocs.Assembly](../../documentassembler)
* perakitan [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
