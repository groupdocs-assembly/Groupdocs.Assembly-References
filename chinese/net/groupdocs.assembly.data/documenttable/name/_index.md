---
title: Name
second_title: GroupDocs.Assembly for .NET API 参考
description: 获取或设置此表的名称用于访问传递给的模板文档中的表数据 DocumentAssemblergroupdocs.assembly/documentassembler.
type: docs
weight: 40
url: /zh/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

获取或设置此表的名称，用于访问传递给的模板文档中的表数据 [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### 评论

如果从文档中读取表的名称，则会自动更正名称以使其有效。 但是，如果通过该属性手动设置表的名称，并且名称无效，则会抛出异常。

如果满足以下条件，则认为该表的名称有效：

* 名字不为空
* 名称的第一个字符是字母或下划线。
* 名称的其余字符是字母、下划线、数字或以下字符：'@'、'#'、'$'.
* 对应的[`DocumentTableSet`](../../documenttableset)对象不包含[`DocumentTable`](../../documenttable)实例 具有相同的名称。

### 也可以看看

* class [DocumentTable](../../documenttable)
* 命名空间 [GroupDocs.Assembly.Data](../../documenttable)
* 部件 [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
