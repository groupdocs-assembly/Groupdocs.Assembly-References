---
title: JsonSimpleValueParseMode
second_title: GroupDocs.Assembly for .NET API リファレンス
description: JSON の読み込み中に JSON の単純な値 nullブール値数値整数および文字列 を解析するためのモードを指定します このようなモードは日時値の解析には影響しません.
type: docs
weight: 160
url: /ja/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

JSON の読み込み中に JSON の単純な値 (null、ブール値、数値、整数、および文字列) を解析するためのモードを指定します。 このようなモードは、日時値の解析には影響しません.

```csharp
public enum JsonSimpleValueParseMode
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Loose | `0` | 文字列表現の解析時に JSON 単純値の型が決定されるモードを指定します。 たとえば、JSON スニペット '{ prop: "123" }' の 'prop' の型は、このモードでは整数として決定されます。 |
| Strict | `1` | JSON 単純な値の型が JSON 表記自体から決定されるモードを指定します。 たとえば、JSON スニペット '{ prop: "123" }' からの 'prop' の型は、このモードでは文字列として決定されます。 |

### 関連項目

* 名前空間 [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* 組み立て [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->