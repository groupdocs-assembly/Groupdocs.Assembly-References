---
title: CsvDataSource
second_title: GroupDocs.Assembly untuk Referensi .NET API
description: Menyediakan akses ke data file atau aliran CSV untuk digunakan saat menyusun dokumen.
type: docs
weight: 30
url: /id/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

Menyediakan akses ke data file atau aliran CSV untuk digunakan saat menyusun dokumen.

```csharp
public class CsvDataSource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | Membuat sumber data baru dengan data dari aliran CSV menggunakan opsi default untuk mengurai data CSV. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | Membuat sumber data baru dengan data dari file CSV menggunakan opsi default untuk menguraikan data CSV. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | Membuat sumber data baru dengan data dari aliran CSV menggunakan opsi yang ditentukan untuk mengurai data CSV. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | Membuat sumber data baru dengan data dari file CSV menggunakan opsi yang ditentukan untuk mengurai data CSV. |

### Perkataan

Untuk mengakses data dari file atau aliran yang sesuai saat menyusun dokumen, berikan instance kelas ini sebagai sumber data ke salah satu[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument kelebihan beban.

Dalam dokumen template, a[`CsvDataSource`](../csvdatasource) instance harus diperlakukan dengan cara yang sama seolah-olah was aDataTablecontoh. Untuk informasi selengkapnya, lihat referensi sintaks template (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Tipe data dari nilai yang dipisahkan koma ditentukan secara otomatis berdasarkan representasi stringnya. Jadi dalam dokumen template , Anda dapat bekerja dengan nilai yang diketik, bukan hanya string. Mesin mampu mengenali nilai secara otomatis dari jenis berikut:

* `panjang?`
* `dobel?`
* `bool?`
* `Tanggal Waktu?`
* `rangkaian`

Perhatikan bahwa agar pengenalan otomatis tipe data berfungsi, representasi string dari nilai yang dipisahkan koma harus dibentuk menggunakan pengaturan budaya invarian.

Untuk mengesampingkan perilaku default pemuatan data CSV, inisialisasi dan berikan a[`CsvDataLoadOptions`](../csvdataloadoptions)instance ke konstruktor kelas ini.

### Lihat juga

* ruang nama [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* perakitan [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
