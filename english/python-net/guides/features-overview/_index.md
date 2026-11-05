---
title: Features Overview
linkTitle: "Features overview"
second_title: GroupDocs.Assembly for Python via .NET API References
description: "GroupDocs.Assembly for Python via .NET builds reports from Word, Excel, PowerPoint, OpenDocument, email, HTML, Markdown and text templates, filled with Python dicts and lists, JSON, XML and CSV files, or the tables of other documents: tables, lists, charts, images, barcodes, hyperlinks and more."
type: docs
url: /python-net/guides/features-overview/
is_root: false
weight: 20
---


GroupDocs.Assembly for Python via .NET generates reports from templates. A template is an ordinary document of one of the [supported formats](/assembly/python-net/guides/supported-document-formats/) whose text holds tags such as `<<[customer.Name]>>` or `<<foreach [o in orders]>>`. Every task follows the same workflow: prepare the data, wrap each data source in a [`DataSourceInfo`](/assembly/python-net/groupdocs.assembly/datasourceinfo/) with the name the template uses, and call `DocumentAssembler.assemble_document()` with the template and the report to write.

## Data sources

Fill a template with:

- **Python data**: dicts, lists, numbers, strings, dates and `Decimal` values, as they are. A dict's keys are read as members (`customer.Name`), a list is a collection to iterate. See [Generate from custom objects](https://docs.groupdocs.com/assembly/python-net/basic-usage-custom-objects/) and [The Business Layer](https://docs.groupdocs.com/assembly/python-net/the-business-layer/).
- **JSON, XML and CSV files** through [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource/), [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource/) and [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource/), which recognize numbers, booleans and dates in the text. See [Working with simple data sources](https://docs.groupdocs.com/assembly/python-net/working-with-simple-data-sources/).
- **The tables of other documents**: a table of a Word document or a presentation, or a worksheet, as a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/), and several related tables of one document as a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/). See [Using documents as data source](https://docs.groupdocs.com/assembly/python-net/using-documents-as-data-source/).
- **Database rows**, turned into dicts in Python. See [Generate from a database](https://docs.groupdocs.com/assembly/python-net/basic-usage-database-datasource/).
- **Several sources in one report**, each under its own name. See [Working with multiple data sources](https://docs.groupdocs.com/assembly/python-net/working-with-multiple-data-sources/).

## Template syntax

Expressions in tags use a subset of C# syntax that works on any data source: arithmetic, comparisons, string operations, the `Sum`, `Count`, `Average`, `Where`, `OrderBy`, `GroupBy` and other sequence operations, and conditional expressions. Format numbers, dates and text in the tag itself, declare variables, and leave comments in a template. See [Template syntax - part 1](/assembly/python-net/guides/template-syntax-part-1-of-2/), [part 2](/assembly/python-net/guides/template-syntax-part-2-of-2/), [Basic template syntax](https://docs.groupdocs.com/assembly/python-net/basic-usage-template-syntax-basics/) and [Enumeration extension methods](https://docs.groupdocs.com/assembly/python-net/enumeration-extension-methods/).

## Reports

- **Tables**: a row per item, with totals, grouping, filtering and ordering, master-detail tables, highlighted rows, alternate content for empty data, merged cells. See [Working with table reports](https://docs.groupdocs.com/assembly/python-net/working-with-table-reports/) and [Generate tables from a collection](https://docs.groupdocs.com/assembly/python-net/basic-usage-generate-tables/).
- **Lists**: bulleted, numbered and multicolored numbered lists, and lists inside a paragraph. See [Generate bullet lists](https://docs.groupdocs.com/assembly/python-net/basic-usage-generate-bullet-lists/) and [Generate numbered lists](https://docs.groupdocs.com/assembly/python-net/basic-usage-generate-numbered-lists/).
- **Charts**: pie, bubble, scatter and column charts whose series, points, colors and titles come from the data. See [Working with chart reports: pie](https://docs.groupdocs.com/assembly/python-net/working-with-chart-reports-pie/) and [Working with chart series coloring](https://docs.groupdocs.com/assembly/python-net/working-with-chart-series-coloring/).
- **Images and barcodes**: pictures named by the data, and barcodes generated from it. See [Inserting images dynamically](https://docs.groupdocs.com/assembly/python-net/inserting-images-dynamically/) and [Working with barcode image generation](https://docs.groupdocs.com/assembly/python-net/working-with-barcode-image-generation/).
- **Hyperlinks, bookmarks, check boxes and other documents**: links and bookmarks built from data, check box and drop-down values, and whole documents inserted into the report. See [Inserting hyperlinks or bookmarks](https://docs.groupdocs.com/assembly/python-net/inserting-hyperlinks-or-bookmarks/), [Set checkbox values dynamically](https://docs.groupdocs.com/assembly/python-net/set-checkbox-values-dynamically/) and [Inserting documents dynamically](https://docs.groupdocs.com/assembly/python-net/inserting-documents-dynamically/).
- **Email messages**: MSG and EML templates whose sender, recipients, subject and body come from the data. See [Generate email messages](https://docs.groupdocs.com/assembly/python-net/basic-usage-generate-emails/).

## Formats

Templates and reports can be Word processing documents, spreadsheets, presentations, OpenDocument files, emails, HTML, Markdown and plain text. A report is saved in the format of its file extension, or of the format you name with [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/), so a Word template can give a PDF or HTML report. See [Supported document formats](/assembly/python-net/guides/supported-document-formats/), [Changing target file format](https://docs.groupdocs.com/assembly/python-net/changing-target-file-format/) and [Using Markdown documents](https://docs.groupdocs.com/assembly/python-net/using-markdown-documents/).

## Assembly options

- Update fields and recalculate formulas while assembling: see [Updating fields](https://docs.groupdocs.com/assembly/python-net/updating-fields-while-assembling-word-processing-documents/) and [Calculate formulas](https://docs.groupdocs.com/assembly/python-net/calculate-formula-while-assembling-spreadsheet-documents/).
- Remove the paragraphs that end up empty: see [Removing empty paragraphs](https://docs.groupdocs.com/assembly/python-net/removing-empty-paragraphs/).
- Write template errors into the report instead of raising: see [In-line syntax error messages](https://docs.groupdocs.com/assembly/python-net/use-of-in-line-syntax-error-messages-into-templates/).
- Allow members the data does not have (`DocumentAssemblyOptions.ALLOW_MISSING_MEMBERS`).

## Loading and saving

Read templates from files or streams and write reports to files or streams, resolve the pictures of an HTML template from a folder of your choice, save an HTML report with its resources in a separate folder, and choose the OOXML compliance level of a Word report. See [Streams vs. file paths](https://docs.groupdocs.com/assembly/python-net/basic-usage-streams-vs-files/), [Loading and saving with external resource files](https://docs.groupdocs.com/assembly/python-net/loading-and-saving-with-external-resource-files/) and [Specify OOXML compliance](https://docs.groupdocs.com/assembly/python-net/basic-usage-ooxml-compliance/).
