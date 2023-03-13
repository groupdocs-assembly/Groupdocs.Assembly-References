---
title: JsonDataLoadOptions
second_title: GroupDocs.Assembly untuk Referensi .NET API
description: Mewakili opsi untuk memparsing data JSON.
type: docs
weight: 140
url: /id/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

Mewakili opsi untuk mem-parsing data JSON.

```csharp
public class JsonDataLoadOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | Menginisialisasi instance baru dari kelas ini dengan opsi default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | Mendapat atau menyetel flag yang menunjukkan apakah sumber data yang dihasilkan akan selalu berisi objek untuk elemen root JSON. Jika elemen akar JSON berisi satu properti kompleks, objek seperti itu tidak dibuat secara default. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | Mendapat atau menyetel format yang tepat untuk mem-parsing nilai tanggal-waktu JSON saat memuat JSON. Standarnya adalah**batal** . |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | Mendapat atau menyetel mode untuk mengurai nilai sederhana JSON (null, boolean, angka, bilangan bulat, dan string) saat memuat JSON. Mode seperti itu tidak memengaruhi penguraian nilai tanggal-waktu. Standarnya adalah Loose . |

### Perkataan

Instance dari kelas ini dapat diteruskan ke konstruktor dari[`JsonDataSource`](../jsondatasource) .

### Lihat juga

* ruang nama [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* perakitan [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->