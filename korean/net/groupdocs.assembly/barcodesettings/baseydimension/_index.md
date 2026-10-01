---
title: "BaseYDimension"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "2D 바코드 모듈 단위의 최소 높이인 기본 y 차원을 가져오거나 설정합니다. 측정 단위는 GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit 입니다."
type: docs
weight: 20
url: /ko/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

2D 바코드 모듈 단위의 최소 높이인 기본 y-차원을 가져오거나 설정합니다. 측정 단위는 [`GraphicsUnit`](../graphicsunit) 입니다.

```csharp
public float BaseYDimension { get; set; }
```

### 비고

일부 유형의 바코드(예: 데이터 매트릭스)는 y-차원을 무시하고 너비와 높이 단위 모두에 x-차원을 사용할 수 있습니다.

템플릿을 통해 바코드 스케일링이 적용되면, 실제 y-차원은 기본 y-차원과 스케일링 계수를 기반으로 계산됩니다.

### 관련 항목

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
