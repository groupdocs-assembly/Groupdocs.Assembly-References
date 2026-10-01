---
title: "GroupDocs.Assembly.Data"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر فئات للوصول إلى بيانات المستندات الخارجية لاستخدامها أثناء تجميع مستند."
type: docs
weight: 20
url: /ar/net/groupdocs.assembly.data/
---
يوفر فئات للوصول إلى بيانات المستندات الخارجية لاستخدامها أثناء تجميع مستند.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | يمثل خيارات لتحليل بيانات CSV. |
| [CsvDataSource](./csvdatasource) | يوفر إمكانية الوصول إلى بيانات ملف CSV أو تدفق لاستخدامها أثناء تجميع المستند. |
| [DocumentTable](./documenttable) | يوفر إمكانية الوصول إلى بيانات جدول واحد (أو جدول بيانات) موجود في مستند خارجي لاستخدامه أثناء تجميع المستند. |
| [DocumentTableCollection](./documenttablecollection) | يمثل مجموعة للقراءة فقط من كائنات [`DocumentTable`](../groupdocs.assembly.data/documenttable) الخاصة بنموذج [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) معين. |
| [DocumentTableColumn](./documenttablecolumn) | يمثل عمودًا واحدًا لكائن [`DocumentTable`](../groupdocs.assembly.data/documenttable) معين. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | يمثل مجموعة للقراءة فقط من كائنات [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) الخاصة بنموذج [`DocumentTable`](../groupdocs.assembly.data/documenttable) معين. |
| [DocumentTableLoadArgs](./documenttableloadargs) | يوفر البيانات للطريقة [`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle). |
| [DocumentTableOptions](./documenttableoptions) | يوفر مجموعة من الخيارات للتحكم في استخراج البيانات من جدول المستند. |
| [DocumentTableRelation](./documenttablerelation) | يمثل علاقة أب-ابن بين كائنين [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | يمثل مجموعة كائنات [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) لنموذج [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) واحد. |
| [DocumentTableSet](./documenttableset) | يوفر إمكانية الوصول إلى بيانات جداول متعددة (أو جداول بيانات) موجودة في مستند خارجي لاستخدامها أثناء تجميع المستند. كما يتيح تعريف علاقات أب-ابن لجداول المستند مما يبسط الوصول إلى البيانات المرتبطة داخل مستندات القالب. |
| [JsonDataLoadOptions](./jsondataloadoptions) | يمثل خيارات لتحليل بيانات JSON. |
| [JsonDataSource](./jsondatasource) | يوفر إمكانية الوصول إلى بيانات ملف JSON أو تدفق لاستخدامها أثناء تجميع المستند. |
| [XmlDataLoadOptions](./xmldataloadoptions) | يمثل خيارات لتحميل بيانات XML. |
| [XmlDataSource](./xmldatasource) | يوفر إمكانية الوصول إلى بيانات ملف XML أو تدفق لاستخدامها أثناء تجميع المستند. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | يتجاوز التحميل الافتراضي لكائنات [`DocumentTable`](../groupdocs.assembly.data/documenttable) أثناء إنشاء نموذج [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | يحدد وضعًا لتحليل القيم البسيطة في JSON (null، boolean، number، integer، وstring) أثناء تحميل JSON. هذا الوضع لا يؤثر على تحليل قيم التاريخ والوقت. |

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
