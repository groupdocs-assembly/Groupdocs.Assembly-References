---
title: Generate sample report for document with variable
linkTitle: "Generate sample report for"
second_title: GroupDocs.Assembly for Python via .NET API References
description: "assembler = ga.DocumentAssembler()"
type: docs
url: /python-net/guides/barcode/
is_root: false
weight: 60
---


## Adding Syntax to be evaluated by GroupDocs.Assembly Engine

**Template Syntax**

```python
assembler = ga.DocumentAssembler()
dataSource = ga.data.XmlDataSource("datasource.xml")
DataSourceInfo = ga.DataSourceInfo(dataSource)
array = [DataSourceInfo]
print(assembler.assemble_document(input.ppt, output.ppt, array))
```

**DataSource XML**
```xml
<Product>
    <Discount>0</Discount>
    <ProductID>1</ProductID>
    <ProductName>LG Nexus 5</ProductName>
    <ProductPrice>350</ProductPrice>
    <UnitsInStock>5</UnitsInStock>
	<Barcode>123456789qwertyu0025</Barcode>
  </Product>
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
