---
title: Name
second_title: GroupDocs.Assembly for .NET API リファレンス
description: に渡されたテンプレート ドキュメント内のテーブルのデータにアクセスするために使用されるこのテーブルの名前を取得または設定しますDocumentAssemblergroupdocs.assembly/documentassembler.
type: docs
weight: 40
url: /ja/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

に渡されたテンプレート ドキュメント内のテーブルのデータにアクセスするために使用されるこのテーブルの名前を取得または設定します。[`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### 備考

テーブルの名前がドキュメントから読み取られた場合、その名前は有効になるように自動的に修正されます。 ただし、テーブルの名前がこのプロパティを介して手動で設定され、名前が無効な場合、例外がスローされます.

次の条件が満たされている場合、テーブルの名前は有効であると見なされます:

* 名前が空ではありません.
* 名前の最初の文字は文字またはアンダースコアです。
* 名前の残りの文字は、文字、アンダースコア、数字、または次の文字です: '@'、'#'、'$'.
* 対応する[`DocumentTableSet`](../../documenttableset)オブジェクトに含まれていない[`DocumentTable`](../../documenttable)同じ名前のインスタンス .

### 関連項目

* class [DocumentTable](../../documenttable)
* 名前空間 [GroupDocs.Assembly.Data](../../documenttable)
* 組み立て [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->