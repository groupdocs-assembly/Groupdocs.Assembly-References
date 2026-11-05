---
title: Generate email report with common list.
linkTitle: "Generate email report with"
second_title: GroupDocs.Assembly for Python via .NET API References
description: "assembler = ga.DocumentAssembler()"
type: docs
url: /python-net/guides/email_reports/
is_root: false
weight: 70
---


## Adding Syntax to be evaluated by GroupDocs.Assembly Engine

**Template Syntax**

```python
assembler = ga.DocumentAssembler()
dataSource = ga.data.JsonDataSource("datasource.json")
DataSourceInfo = ga.DataSourceInfo(dataSource, "customers")
array = [DataSourceInfo, ga.DataSourceInfo(["test@test.mail", "groupdocs@groupdocs.mail"], "recipients"), ga.DataSourceInfo("sender@sender.mail", "sender"), ga.DataSourceInfo("cc@example.com", "cc"), ga.DataSourceInfo("groupdocs", "subject")]
print(assembler.assemble_document("input.msg", "output.msg", array))
```

## The Recipe

*   Set up the source document data path
*   Set up the source document template path
*   Set up destination report path
*   Instantiate [DocumentAssembler](https://reference.groupdocs.com/python-net/assembly/groupdocs.assembly/documentassembler) class
*   Generate report

## More resources

### Advanced usage topics

To learn more about library features, please refer to the[advanced usage section](https://docs.groupdocs.com/assembly/python-net/advanced-usage/).

### GitHub examples

You may easily run the code above and see the feature in action in our GitHub examples:

*   [GroupDocs.Assembly for .NET examples](https://github.com/groupdocs-assembly/GroupDocs.Assembly-for-.NET)
    
*   [GroupDocs.Assembly for Java examples](https://github.com/groupdocs-assembly/GroupDocs.Assembly-for-Java)

*   [GroupDocs.Assembly for Python via .NET examples](https://github.com/groupdocs-assembly/GroupDocs.Assembly-for-Python-via-.NET)
