---
title: IDocumentTableLoadHandler
second_title: GroupDocs.Assembly for .NET API リファレンス
description: のデフォルトの読み込みを上書きしますDocumentTable./documenttable作成中のオブジェクトDocumentTableSet./documenttableset インスタンス.
type: docs
weight: 130
url: /ja/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

のデフォルトの読み込みを上書きします[`DocumentTable`](../documenttable)作成中のオブジェクト[`DocumentTableSet`](../documenttableset) インスタンス.

```csharp
public interface IDocumentTableLoadHandler
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | 特定のデフォルトの読み込みを上書きします[`DocumentTable`](../documenttable) a の作成中のオブジェクト[`DocumentTableSet`](../documenttableset)インスタンス. |

### 備考

特定の読み込みを破棄したい場合は、このインターフェースを実装してください。[`DocumentTable`](../documenttable)オブジェクトまたは 固有の提供[`DocumentTableOptions`](../documenttableoptions)ロード中のドキュメント テーブル用.

### 関連項目

* 名前空間 [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* 組み立て [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
