---
title: XmlDataSource
second_title: GroupDocs.Assembly for .NET API 参考
description: 提供对 XML 文件或流的数据的访问以在组装文档时使用
type: docs
weight: 180
url: /zh/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

提供对 XML 文件或流的数据的访问，以在组装文档时使用。

```csharp
public class XmlDataSource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | 使用 XML 数据加载的默认选项使用 XML 流中的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_4)(string) | 使用 XML 数据加载的默认选项使用 XML 文件中的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | 使用 XML 架构定义流使用来自 XML 流的数据创建新数据源。默认 options 用于 XML 数据加载。 |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | 使用 XML 数据加载的指定选项使用 XML 流中的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | 使用 XML 架构定义文件使用 XML 文件中的数据创建新数据源。默认 options 用于 XML 数据加载。 |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | 使用 XML 数据加载的指定选项使用 XML 文件中的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | 使用 XML 架构定义流使用来自 XML 流的数据创建新数据源。指定的 选项用于加载 XML 数据。 |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | 使用 XML 架构定义文件使用 XML 文件中的数据创建新数据源。指定的 选项用于加载 XML 数据。 |

### 评论

要在组装文档时访问相应文件或流的数据，请将此类的实例作为 数据源传递给其中一个[`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 重载.

在模板文档中，如果顶级 XML 元素只包含相同类型的元素列表， [`XmlDataSource`](../xmldatasource)实例应以与 a相同的方式处理DataTable实例。否则，一个[`XmlDataSource`](../xmldatasource)实例应该被 对待，就像它是DataRow实例。有关详细信息， 请参阅模板语法参考 (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)。

当XML Schema Definition 被传递给该类的构造函数时，简单XML 元素 的值的数据类型和属性是根据模式确定的。因此，在模板文档中，您可以使用类型值 而不仅仅是字符串。

当 XML Schema Definition 不传递给此类的构造函数时，简单 XML 元素 和属性的值的数据类型将根据其字符串表示形式自动确定。因此，在模板文档中，您也可以在这种情况下使用 使用键入的值。该引擎能够自动识别以下类型的值：

* Nullable
* Nullable
* Nullable
* Nullable
* String

请注意，为了自动识别数据类型，简单 XML 元素 和属性的值的字符串表示应使用不变的文化设置形成。

要覆盖 XML 数据加载的默认行为，初始化并传递一个[`XmlDataLoadOptions`](../xmldataloadoptions) 实例到此类的构造函数。

### 也可以看看

* 命名空间 [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* 部件 [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->