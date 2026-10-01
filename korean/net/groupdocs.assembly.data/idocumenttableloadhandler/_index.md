---
title: "IDocumentTableLoadHandler"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "DocumentTableSet./documenttableset 인스턴스를 생성하는 동안 DocumentTable./documenttable 객체의 기본 로드를 재정의합니다."
type: docs
weight: 210
url: /ko/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

[`DocumentTableSet`](../documenttableset) 인스턴스를 생성하는 동안 [`DocumentTable`](../documenttable) 객체의 기본 로드를 재정의합니다.

```csharp
public interface IDocumentTableLoadHandler
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | [`DocumentTableSet`](../documenttableset) 인스턴스를 생성하는 동안 특정 [`DocumentTable`](../documenttable) 객체의 기본 로드를 재정의합니다. |

### 비고

특정 [`DocumentTable`](../documenttable) 객체의 로드를 제외하거나 로드되는 문서 테이블에 대해 특정 [`DocumentTableOptions`](../documenttableoptions)를 제공하려면 이 인터페이스를 구현하십시오.

### 관련 항목

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
