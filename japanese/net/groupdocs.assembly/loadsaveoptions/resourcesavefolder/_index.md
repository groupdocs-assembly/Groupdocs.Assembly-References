---
title: ResourceSaveFolder
second_title: GroupDocs.Assembly for .NET API リファレンス
description: HTML 以外の 形式から読み込まれたアセンブルされたドキュメントを HTML に保存する際に外部リソース ファイルを格納するフォルダーへのパスを取得または設定しますデフォルト値は空の文字列です
type: docs
weight: 30
url: /ja/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

HTML 以外の 形式から読み込まれたアセンブルされたドキュメントを HTML に保存する際に、外部リソース ファイルを格納するフォルダーへのパスを取得または設定します。デフォルト値は空の文字列です。

```csharp
public string ResourceSaveFolder { get; set; }
```

### 備考

デフォルトでは、アセンブルされたドキュメントを HTML ファイルに保存する場合、外部リソース ファイルは、HTML ファイルと同じ名前で、拡張子に「_files」サフィックスを付けたものを除いたフォルダー に保存されます。このフォルダーは、HTML ファイルと同じフォルダー内の にあります。ただし、これは、アセンブルされたドキュメントを HTML ストリームに保存する場合には実行できません。ドキュメントを HTML ファイルにアセンブルします。

HTML に保存されているアセンブルされたドキュメントが HTML から読み込まれた場合、このプロパティの値は無視されます (外部リソース ファイルは保存されず、それらへのリンクは変更されません)。

### 関連項目

* class [LoadSaveOptions](../../loadsaveoptions)
* 名前空間 [GroupDocs.Assembly](../../loadsaveoptions)
* 組み立て [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->