---
title: "이름"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "템플릿 문서에서 데이터 소스 개체에 접근하기 위해 사용할 데이터 소스 개체의 이름을 가져오거나 설정합니다."
type: docs
weight: 30
url: /ko/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

템플릿 문서에서 데이터 소스 개체에 접근하기 위해 사용할 데이터 소스 개체의 이름을 가져오거나 설정합니다.

```csharp
public string Name { get; set; }
```

### 비고

데이터 소스 객체의 이름이 지정된 경우, 해당 이름을 사용하여 템플릿 문서에서 데이터 소스 객체와 그 멤버에 접근할 수 있습니다.

데이터 소스 객체의 이름이 null이거나 비어 있는 경우에도 컨텍스트 객체 멤버 접근(자세한 내용은 Template Syntax Reference를 참조)을 사용하여 템플릿 문서에서 데이터 소스 객체의 멤버에 접근할 수 있지만, 데이터 소스 객체 자체에는 접근할 수 없습니다.

여러 개의 [`DataSourceInfo`](../../datasourceinfo) 인스턴스를 [`DocumentAssembler`](../../documentassembler)에 전달할 때, 첫 번째 데이터 소스 객체의 이름만 null이거나 비어 있을 수 있습니다. 나머지 객체들의 이름은 지정되어야 하며 고유해야 합니다.

### 관련 항목

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
