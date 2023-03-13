---
title: Name
second_title: GroupDocs.Assembly for .NET API リファレンス
description: テンプレート ドキュメント内のデータ ソース オブジェクトへのアクセスに使用されるデータ ソース オブジェクトの名前を取得または設定します
type: docs
weight: 30
url: /ja/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

テンプレート ドキュメント内のデータ ソース オブジェクトへのアクセスに使用されるデータ ソース オブジェクトの名前を取得または設定します。

```csharp
public string Name { get; set; }
```

### 備考

データ ソース オブジェクトの名前を指定すると、名前を使用してテンプレート ドキュメント内のデータ ソース オブジェクトとそのメンバー にアクセスできます。

データ ソース オブジェクトの名前が null または空の場合でも、コンテキスト オブジェクト メンバー アクセスを使用してテンプレート ドキュメント内のデータ ソース オブジェクト のメンバーにアクセスできます (詳細については、テンプレート シンタックス リファレンスを参照してください)。データ ソース オブジェクト自体.

複数渡す場合[`DataSourceInfo`](../../datasourceinfo)インスタンスへ[`DocumentAssembler`](../../documentassembler)、 の名前のみ、最初のデータ ソース オブジェクトは null または空にすることができます。残りの名前は、指定して一意にする必要があります.

### 関連項目

* class [DataSourceInfo](../../datasourceinfo)
* 名前空間 [GroupDocs.Assembly](../../datasourceinfo)
* 組み立て [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->