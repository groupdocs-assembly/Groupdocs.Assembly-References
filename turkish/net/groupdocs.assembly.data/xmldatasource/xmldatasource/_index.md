---
title: XmlDataSource
second_title: .NET API Başvurusu için GroupDocs.Assembly
description: XML veri yükleme için varsayılan seçenekleri kullanarak bir XML dosyasındaki verilerle yeni bir veri kaynağı oluşturur.
type: docs
weight: 10
url: /tr/net/groupdocs.assembly.data/xmldatasource/xmldatasource/
---
## XmlDataSource(string) {#constructor_4}

XML veri yükleme için varsayılan seçenekleri kullanarak bir XML dosyasındaki verilerle yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(string xmlPath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |

### Ayrıca bakınız

* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream) {#constructor}

XML veri yükleme için varsayılan seçenekleri kullanarak bir XML akışındaki verilerle yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(Stream xmlStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML veri akışı. |

### Ayrıca bakınız

* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string) {#constructor_6}

Bir XML Şema Tanımı dosyası kullanarak bir XML dosyasındaki verilerle yeni bir veri kaynağı oluşturur. Varsayılan options , XML veri yüklemesi için kullanılır.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |
| xmlSchemaPath | String | XML dosyası için şema sağlayan XML Şema Tanımı dosyasının yolu. |

### Ayrıca bakınız

* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream) {#constructor_2}

XML Şema Tanımı akışını kullanarak bir XML akışından alınan verilerle yeni bir veri kaynağı oluşturur. Varsayılan options , XML veri yüklemesi için kullanılır.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML veri akışı. |
| xmlSchemaStream | Stream | XML verileri için şema sağlayan XML Şema Tanımı akışı. |

### Ayrıca bakınız

* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, XmlDataLoadOptions) {#constructor_5}

XML veri yükleme için belirtilen seçenekleri kullanarak bir XML dosyasındaki verilerle yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(string xmlPath, XmlDataLoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, XmlDataLoadOptions) {#constructor_1}

XML veri yükleme için belirtilen seçenekleri kullanarak bir XML akışındaki verilerle yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(Stream xmlStream, XmlDataLoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML veri akışı. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string, XmlDataLoadOptions) {#constructor_7}

Bir XML Şema Tanımı dosyası kullanarak bir XML dosyasındaki verilerle yeni bir veri kaynağı oluşturur. Belirtilen seçenekleri, XML verilerinin yüklenmesi için kullanılır.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath, XmlDataLoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |
| xmlSchemaPath | String | XML dosyası için şema sağlayan XML Şema Tanımı dosyasının yolu. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream, XmlDataLoadOptions) {#constructor_3}

XML Şema Tanımı akışını kullanarak bir XML akışından alınan verilerle yeni bir veri kaynağı oluşturur. Belirtilen seçenekleri, XML verilerinin yüklenmesi için kullanılır.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream, XmlDataLoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML veri akışı. |
| xmlSchemaStream | Stream | XML verileri için şema sağlayan XML Şema Tanımı akışı. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* ad alanı [GroupDocs.Assembly.Data](../../xmldatasource)
* toplantı [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
