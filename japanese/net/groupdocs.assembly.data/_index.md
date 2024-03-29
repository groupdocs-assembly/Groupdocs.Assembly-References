---
title: GroupDocs.Assembly.Data
second_title: GroupDocs.Assembly for .NET API リファレンス
description: ドキュメントのアセンブル中に使用される外部ドキュメントのデータにアクセスするためのクラスを提供します
type: docs
weight: 20
url: /ja/net/groupdocs.assembly.data/
---
ドキュメントのアセンブル中に使用される外部ドキュメントのデータにアクセスするためのクラスを提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [CsvDataLoadOptions](./csvdataloadoptions) | CSV データを解析するためのオプションを表します。 |
| [CsvDataSource](./csvdatasource) | ドキュメントのアセンブル中に使用される CSV ファイルまたはストリームのデータへのアクセスを提供します。 |
| [DocumentTable](./documenttable) | 外部ドキュメントにある単一のテーブル (またはスプレッドシート) のデータへのアクセスを提供し、 ドキュメントのアセンブル中に使用されます. |
| [DocumentTableCollection](./documenttablecollection) | の読み取り専用コレクションを表します[`DocumentTable`](../groupdocs.assembly.data/documenttable)特定のオブジェクト[`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) インスタンス. |
| [DocumentTableColumn](./documenttablecolumn) | 特定の単一の列を表します[`DocumentTable`](../groupdocs.assembly.data/documenttable)object. |
| [DocumentTableColumnCollection](./documenttablecolumncollection) | の読み取り専用コレクションを表します[`DocumentTableColumn`](../groupdocs.assembly.data/documenttablecolumn)特定の のオブジェクト[`DocumentTable`](../groupdocs.assembly.data/documenttable)インスタンス. |
| [DocumentTableLoadArgs](./documenttableloadargs) | のデータを提供します[`Handle`](../groupdocs.assembly.data/idocumenttableloadhandler/handle)method. |
| [DocumentTableOptions](./documenttableoptions) | ドキュメント テーブルからのデータの抽出を制御する一連のオプションを提供します。 |
| [DocumentTableRelation](./documenttablerelation) | 2 つの間の親子関係を表します[`DocumentTable`](../groupdocs.assembly.data/documenttable)オブジェクト. |
| [DocumentTableRelationCollection](./documenttablerelationcollection) | のコレクションを表します[`DocumentTableRelation`](../groupdocs.assembly.data/documenttablerelation)単一のオブジェクト[`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) インスタンス. |
| [DocumentTableSet](./documenttableset) | 外部ドキュメントにある複数のテーブル (またはスプレッドシート) のデータへのアクセスを提供し、 ドキュメントのアセンブル中に使用します。また、ドキュメント テーブルの親子関係を定義できるため、 テンプレート ドキュメント内の関連データへのアクセスが簡素化されます. |
| [JsonDataLoadOptions](./jsondataloadoptions) | JSON データを解析するためのオプションを表します。 |
| [JsonDataSource](./jsondatasource) | ドキュメントのアセンブル中に使用される JSON ファイルまたはストリームのデータへのアクセスを提供します。 |
| [XmlDataLoadOptions](./xmldataloadoptions) | XML データ読み込みのオプションを表します。 |
| [XmlDataSource](./xmldatasource) | ドキュメントのアセンブル中に使用される XML ファイルまたはストリームのデータへのアクセスを提供します。 |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IDocumentTableLoadHandler](./idocumenttableloadhandler) | のデフォルトの読み込みを上書きします[`DocumentTable`](../groupdocs.assembly.data/documenttable)作成中のオブジェクト[`DocumentTableSet`](../groupdocs.assembly.data/documenttableset) インスタンス. |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [JsonSimpleValueParseMode](./jsonsimplevalueparsemode) | JSON の読み込み中に JSON の単純な値 (null、ブール値、数値、整数、および文字列) を解析するためのモードを指定します。 このようなモードは、日時値の解析には影響しません. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
