---
title: JsonDataSource
second_title: GroupDocs.Assembly for .NET API 参考
description: 提供对在组装文档时要使用的 JSON 文件或流的数据的访问
type: docs
weight: 150
url: /zh/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

提供对在组装文档时要使用的 JSON 文件或流的数据的访问。

```csharp
public class JsonDataSource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | 使用用于解析 JSON 数据的默认选项使用来自 JSON 流的数据创建新数据源。 |
| [JsonDataSource](jsondatasource#constructor_2)(string) | 使用用于解析 JSON 数据的默认选项使用来自 JSON 文件的数据创建新数据源。 |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | 使用用于解析 JSON 数据的指定选项使用来自 JSON 流的数据创建新数据源。 |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | 使用用于解析 JSON 数据的指定选项使用 JSON 文件中的数据创建新数据源。 |

### 评论

要在组装文档时访问相应文件或流的数据，将此类的实例作为 数据源传递给其中之一[`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 重载.

在模板文档中，如果顶级 JSON 元素是数组，则[`JsonDataSource`](../jsondatasource)实例应该 以与它是一个相同的方式对待DataTable实例。如果顶级 JSON 元素 是一个对象，则[`JsonDataSource`](../jsondatasource)实例应该以与 a 相同的方式对待DataRow实例。有关详细信息，请参阅模板语法参考 (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

在模板文档中，您可以使用 JSON 元素的类型化值。为方便起见，引擎将 JSON 简单类型的集合 替换为以下一个：

* `长的？`
* `双倍的？`
* `布尔？`
* `约会时间？`
* `细绳`

引擎根据 JSON 表示自动识别额外类型的值。

要覆盖 JSON 数据加载的默认行为，初始化并传递一个[`JsonDataLoadOptions`](../jsondataloadoptions)instance 到此类的构造函数.

### 也可以看看

* 命名空间 [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* 部件 [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
