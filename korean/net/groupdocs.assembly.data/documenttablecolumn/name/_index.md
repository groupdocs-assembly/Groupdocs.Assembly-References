---
title: "이름"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "`DocumentAssemblergroupdocs.assembly/documentassembler`에 전달된 템플릿 문서에서 열 데이터를 액세스하는 데 사용되는 이 열의 이름을 가져오거나 설정합니다."
type: docs
weight: 30
url: /ko/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

[`DocumentAssembler`](../../../groupdocs.assembly/documentassembler)에 전달된 템플릿 문서에서 열 데이터를 액세스하는 데 사용되는 이 열의 이름을 가져오거나 설정합니다.

```csharp
public string Name { get; set; }
```

### 비고

열 이름이 문서에서 읽히는 경우([`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames) 참조), 이름이 자동으로 수정되어 유효하게 됩니다. 그러나 이 속성을 통해 열 이름을 수동으로 설정하고 이름이 유효하지 않으면 예외가 발생합니다.

다음 조건이 충족되면 열 이름은 유효한 것으로 간주됩니다:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### 관련 항목

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
