---
title: XmlDataSource
second_title: GroupDocs.Assembly for .NET API 参考
description: 提供对在组装文档时要使用的 XML 文件或流的数据的访问
type: docs
weight: 180
url: /zh/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

提供对在组装文档时要使用的 XML 文件或流的数据的访问。

```csharp
public class XmlDataSource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | 使用 XML 数据加载的默认选项使用来自 XML 流的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_4)(string) | 使用 XML 数据加载的默认选项使用 XML 文件中的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | 使用 XML 架构定义流使用来自 XML 流的数据创建新数据源。默认 options 用于 XML 数据加载。 |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | 使用指定的 XML 数据加载选项使用来自 XML 流的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | 使用 XML 架构定义文件使用来自 XML 文件的数据创建新数据源。默认 options 用于 XML 数据加载。 |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | 使用指定的 XML 数据加载选项使用 XML 文件中的数据创建新数据源。 |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | 使用 XML 架构定义流使用来自 XML 流的数据创建新数据源。指定的 选项用于加载 XML 数据。 |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | 使用 XML 架构定义文件使用来自 XML 文件的数据创建新数据源。指定的 选项用于加载 XML 数据。 |

### 评论

要在组装文档时访问相应文件或流的数据，将此类的实例作为 数据源传递给其中之一[`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument 重载.

在模板文档中，如果顶级 XML 元素仅包含相同类型的元素列表， 一个[`XmlDataSource`](../xmldatasource)实例应该以与 a 相同的方式对待DataTable实例。否则，一个[`XmlDataSource`](../xmldatasource) 实例应该像对待它一样对待DataRow实例。有关详细信息， 请参阅模板语法参考 (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

当 XML 架构定义传递给此类的构造函数时，简单 XML 元素值 和属性的数据类型根据架构确定。因此，在模板文档中，您可以使用类型化值 而不仅仅是字符串。

当 XML 架构定义未传递给此类的构造函数时，简单 XML 元素值的数据类型 和属性将根据其字符串表示形式自动确定。因此，在模板文档中，您也可以在这种情况下使用键入的值来处理 。引擎能够自动识别以下类型的值：

* `长的？`
* `双倍的？`
* `布尔？`
* `约会时间？`
* `细绳`

请注意，要使数据类型自动识别正常工作，简单 XML 元素值的字符串表示形式 和属性应使用不变的区域性设置来形成。

要覆盖 XML 数据加载的默认行为，初始化并传递一个[`XmlDataLoadOptions`](../xmldataloadoptions) 实例到此类的构造函数。

### 也可以看看

* 命名空间 [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* 部件 [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
