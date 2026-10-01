---
title: "GroupDocs.Assembly.Data"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona clases para acceder a los datos de documentos externos que se utilizarán al ensamblar un documento."
type: docs
weight: 20
url: /es/net/groupdocs.assembly.data/
---
Proporciona clases para acceder a los datos de documentos externos que se utilizarán al ensamblar un documento.

## Clases

| Clase | Descripción |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | Representa opciones para analizar datos CSV. |
| [CsvDataSource](./csvdatasource) | Proporciona acceso a los datos de un archivo CSV o flujo para ser utilizados al ensamblar un documento. |
| [DocumentTable](./documenttable) | Proporciona acceso a los datos de una única tabla (o hoja de cálculo) ubicada en un documento externo para ser utilizada al ensamblar un documento. |
| [DocumentTableCollection](./documenttablecollection) | Representa una colección de solo lectura de objetos [`DocumentTable`](../groupdocs.assembly.data/documenttable) de una instancia particular de [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
| [DocumentTableColumn](./documenttablecolumn) | Representa una única columna de un objeto [`DocumentTable`](../groupdocs.assembly.data/documenttable) particular. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | Representa una colección de solo lectura de objetos [`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn) de una instancia particular de [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableLoadArgs](./documenttableloadargs) | Proporciona datos para el método [`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle). |
| [DocumentTableOptions](./documenttableoptions) | Proporciona un conjunto de opciones para controlar la extracción de datos de una tabla de documento. |
| [DocumentTableRelation](./documenttablerelation) | Representa una relación padre-hijo entre dos objetos [`DocumentTable`](../groupdocs.assembly.data/documenttable). |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | Representa la colección de objetos [`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation) de una única instancia de [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
| [DocumentTableSet](./documenttableset) | Proporciona acceso a los datos de múltiples tablas (o hojas de cálculo) ubicadas en un documento externo para ser utilizadas al ensamblar un documento. Además, permite definir relaciones padre-hijo para las tablas de documento, simplificando así el acceso a datos relacionados dentro de los documentos plantilla. |
| [JsonDataLoadOptions](./jsondataloadoptions) | Representa opciones para analizar datos JSON. |
| [JsonDataSource](./jsondatasource) | Proporciona acceso a los datos de un archivo JSON o flujo para ser utilizados al ensamblar un documento. |
| [XmlDataLoadOptions](./xmldataloadoptions) | Representa opciones para la carga de datos XML. |
| [XmlDataSource](./xmldatasource) | Proporciona acceso a los datos de un archivo XML o flujo para ser utilizados al ensamblar un documento. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | Sobrescribe la carga predeterminada de objetos [`DocumentTable`](../groupdocs.assembly.data/documenttable) al crear una instancia de [`DocumentTableSet`](../groupdocs.assembly.data/documenttableset). |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | Especifica un modo para analizar valores simples JSON (null, booleano, número, entero y cadena) al cargar JSON. Este modo no afecta el análisis de valores de fecha y hora. |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
