---
title: DocumentAssembler
second_title: GroupDocs.Assembly for .NET API リファレンス
description: テンプレート ドキュメントにデータを入力するルーチンとこれらのルーチンを制御する一連の設定を提供します
type: docs
weight: 200
url: /ja/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

テンプレート ドキュメントにデータを入力するルーチンと、これらのルーチンを制御する一連の設定を提供します。

```csharp
public class DocumentAssembler
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DocumentAssembler](documentassembler)() | このクラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | ドキュメントのアセンブル中にバーコード生成を制御する一連の設定を取得します。 |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | を含む順序付けられていないセット (つまり、一意のアイテムのコレクション) を取得します。Typeオブジェクト は、この アセンブラー インスタンスによって処理されるドキュメント テンプレート内で完全または部分的に修飾された名前を使用して、対応する型の静的メンバーを呼び出したり、型キャストを実行したりできます。 |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | この動作を制御する一連のフラグを取得または設定します[`DocumentAssembler`](../documentassembler)ドキュメントのアセンブル中のインスタンス . |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | リフレクション API を介して実行されるカスタム型メンバーの呼び出しが動的クラス生成を使用して 最適化されているかどうかを示す値を取得または設定します。デフォルト値は true. です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | 指定されたソース ストリームからテンプレート ドキュメントをロードし、 指定された単一または複数のソースからのデータをテンプレート ドキュメントに入力し、default を使用して結果ドキュメントをターゲット ストリームに保存します。[`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | 指定されたソース パスからテンプレート ドキュメントを読み込み、 指定された単一または複数のソースからのデータをテンプレート ドキュメントに入力し、default を使用して結果ドキュメントをターゲット パスに保存します。[`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | 指定されたソース ストリームからテンプレート ドキュメントを読み込み、 指定された単一または複数のソースからのデータをテンプレート ドキュメントに入力し、指定された を使用して結果ドキュメントをターゲット ストリームに保存します。[`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | 指定されたソース パスからテンプレート ドキュメントを読み込み、 指定された単一または複数のソースからのデータをテンプレート ドキュメントに入力し、指定された を使用して結果ドキュメントをターゲット パスに保存します。[`LoadSaveOptions`](../loadsaveoptions). |

### 関連項目

* 名前空間 [GroupDocs.Assembly](../../groupdocs.assembly)
* 組み立て [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->