---
title: Adding NEXT Field into Template Syntax
linkTitle: "Adding NEXT Field into Template"
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Adding NEXT Field into Template Syntax with GroupDocs.Assembly for Python via .NET: the template, the Python data and the code."
type: docs
url: /python-net/guides/adding-next-field-into-template-syntax/
is_root: false
weight: 60
---


The example reads the shop data described in [The Business Layer](https://docs.groupdocs.com/assembly/python-net/the-business-layer/).

## Adding Syntax to be evaluated by GroupDocs.Assembly Engine

**Template Syntax**

```text
We provide support for the following products:
. <<foreach [in products]>><<next>><<[ProductName]>>
<</foreach>>
```

## The Recipe

*   Set up the source document template path
*   Set up destination report path
*   Instantiate [DocumentAssembler](https://reference.groupdocs.com/assembly/python-net/groupdocs.assembly/documentassembler/) class
*   Generate report

### Download Template

Get the template from here.

*   [next-field.docx](https://docs.groupdocs.com/assembly/python-net/_sample_files/developer-guide/advanced-usage/adding-next-field-into-template-syntax/next-field.docx)

### The Code

{{< tabs "example1" >}}
{{< tab "Python" >}}
```python
import json

from groupdocs.assembly import DataSourceInfo, DocumentAssembler

with open("products.json", encoding="utf-8") as f:
    products = json.load(f)

assembler = DocumentAssembler()
assembler.assemble_document("next-field.docx", "next-field-report.docx", DataSourceInfo(products, "product"))
```
{{< /tab >}}
{{< tab "next-field.docx" >}}

The following sample file is used in this example: [next-field.docx](https://docs.groupdocs.com/assembly/python-net/_sample_files/developer-guide/advanced-usage/adding-next-field-into-template-syntax/next-field.docx)

{{< /tab >}}
{{< tab "products.json" >}}

The following sample file is used in this example: [products.json](https://docs.groupdocs.com/assembly/python-net/_sample_files/developer-guide/advanced-usage/adding-next-field-into-template-syntax/products.json)

{{< /tab >}}
{{< tab "next-field-report.docx" >}}  
```text
Binary file (DOCX, 11 KB)
```
[Download full output](https://docs.groupdocs.com/assembly/python-net/_output_files/developer-guide/advanced-usage/adding-next-field-into-template-syntax/the_code/next-field-report.docx)
{{< /tab >}}
{{< /tabs >}}
