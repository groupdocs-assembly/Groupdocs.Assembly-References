---
title: Adding NEXT Field into Template Syntax
linkTitle: "Adding NEXT Field into Template"
second_title: GroupDocs.Assembly for Python via .NET API References
description: "We provide support for the following products:"
type: docs
url: /python-net/guides/adding-next-field-into-template-syntax/
is_root: false
weight: 80
---


This feature is only compatible with GroupDocs.Assembly for Python via .NET 3.3.0 or later releases.

## Adding Syntax to be evaluated by GroupDocs.Assembly Engine

**Template Syntax**

```python
We provide support for the following products:
. <<foreach [in products]>><<next>><<[ProductName]>>
<</foreach>>
```

## The Recipe

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
