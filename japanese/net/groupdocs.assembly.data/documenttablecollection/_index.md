---
title: DocumentTableCollection
second_title: GroupDocs.Assembly for .NET API リファレンス
description: の読み取り専用コレクションを表しますDocumentTable./documenttable特定のオブジェクトDocumentTableSet./documenttableset インスタンス.
type: docs
weight: 50
url: /ja/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

の読み取り専用コレクションを表します[`DocumentTable`](../documenttable)特定のオブジェクト[`DocumentTableSet`](../documenttableset) インスタンス.

```csharp
public class DocumentTableCollection : IEnumerable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | の総数を取得します[`DocumentTable`](../documenttable)コレクション内のオブジェクト. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | を取得します[`DocumentTable`](../documenttable)指定された index. のコレクションからのインスタンス (2 indexers) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | このコレクションに指定されたテーブルが含まれているかどうかを示す値を返します。 |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | このコレクションに指定された名前のテーブルが含まれているかどうかを示す値を返します。 |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | 反復する列挙子を返します[`DocumentTable`](../documenttable)このコレクションのオブジェクト. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | このコレクション内の指定されたテーブルのインデックスを返します。 |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | このコレクション内の指定された名前を持つテーブルのインデックスを返します。 |

### 備考

コレクションは、ドキュメントから対応するテーブルをロードする際に自動的に入力され、変更することはできません. ただし、のプロパティ[`DocumentTable`](../documenttable)コレクション内に含まれるオブジェクトを変更できます.

### 関連項目

* 名前空間 [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* 組み立て [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->