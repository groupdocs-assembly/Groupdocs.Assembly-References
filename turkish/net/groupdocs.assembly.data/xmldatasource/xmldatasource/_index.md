---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "XML dosyasından gelen verilerle, XML veri yüklemesi için varsayılan seçenekleri kullanarak yeni bir veri kaynağı oluşturur."
type: docs
weight: 10
url: /tr/net/groupdocs.assembly.data/xmldatasource/xmldatasource/
---
## XmlDataSource(string) {#constructor_4}

XML dosyasından gelen verilerle, XML veri yüklemesi için varsayılan seçenekleri kullanarak yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(string xmlPath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |

### Ayrıca Bakınız

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream) {#constructor}

XML akışından gelen verilerle, XML veri yüklemesi için varsayılan seçenekleri kullanarak yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(Stream xmlStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML verisinin akışı. |

### Ayrıca Bakınız

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string) {#constructor_6}

Bir XML Şema Tanımı dosyası kullanarak bir XML dosyasından veri ile yeni bir veri kaynağı oluşturur. XML veri yüklemesi için varsayılan seçenekler kullanılır.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |
| xmlSchemaPath | String | XML dosyasına şema sağlayan XML Şema Tanımı dosyasının yolu. |

### Ayrıca Bakınız

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream) {#constructor_2}

XML akışından gelen verilerle bir XML Şema Tanımı akışı kullanarak yeni bir veri kaynağı oluşturur. XML veri yüklemesi için varsayılan seçenekler kullanılır.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML verisinin akışı. |
| xmlSchemaStream | Stream | XML verisine şema sağlayan XML Şema Tanımı akışı. |

### Ayrıca Bakınız

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, XmlDataLoadOptions) {#constructor_5}

Belirtilen XML veri yükleme seçeneklerini kullanarak bir XML dosyasından veri ile yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(string xmlPath, XmlDataLoadOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca Bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, XmlDataLoadOptions) {#constructor_1}

Belirtilen XML veri yükleme seçeneklerini kullanarak bir XML akışından veri ile yeni bir veri kaynağı oluşturur.

```csharp
public XmlDataSource(Stream xmlStream, XmlDataLoadOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML verisinin akışı. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca Bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string, XmlDataLoadOptions) {#constructor_7}

Bir XML Şema Tanımı dosyası kullanarak bir XML dosyasından veri ile yeni bir veri kaynağı oluşturur. Belirtilen seçenekler XML veri yüklemesi için kullanılır.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath, XmlDataLoadOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlPath | String | Veri kaynağı olarak kullanılacak XML dosyasının yolu. |
| xmlSchemaPath | String | XML dosyasına şema sağlayan XML Şema Tanımı dosyasının yolu. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca Bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream, XmlDataLoadOptions) {#constructor_3}

Bir XML Şema Tanımı akışı kullanarak bir XML akışından veri ile yeni bir veri kaynağı oluşturur. Belirtilen seçenekler XML veri yüklemesi için kullanılır.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream, XmlDataLoadOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlStream | Stream | Veri kaynağı olarak kullanılacak XML verisinin akışı. |
| xmlSchemaStream | Stream | XML verisine şema sağlayan XML Şema Tanımı akışı. |
| options | XmlDataLoadOptions | XML veri yükleme seçenekleri. |

### Ayrıca Bakınız

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
