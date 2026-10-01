---
title: "BarcodeSettings"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "문서를 조립하는 동안 바코드 생성을 제어하는 설정 집합을 나타냅니다."
type: docs
weight: 10
url: /ko/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

문서를 조립하는 동안 바코드 생성을 제어하는 설정 집합을 나타냅니다.

```csharp
public class BarcodeSettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | 바코드 바와 공백 단위의 최소 너비인 기본 x-차원을 가져오거나 설정합니다. [`GraphicsUnit`](./graphicsunit)으로 측정됩니다. |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | 2D 바코드 모듈 단위의 최소 높이인 기본 y-차원을 가져오거나 설정합니다. [`GraphicsUnit`](./graphicsunit)으로 측정됩니다. |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | [`BaseXDimension`](./basexdimension) 및 [`BaseYDimension`](./baseydimension)을 측정하는 그래픽 단위를 가져오거나 설정합니다. 기본값은 Millimeter입니다. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | 생성되는 바코드 이미지의 가로 및 세로 해상도를 가져오거나 설정합니다. 인치당 점(dot per inch)으로 측정됩니다. 기본값은 96입니다. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | 잘못된 바코드 값이 바코드 사양에 맞게 자동으로(가능한 경우) 수정되어야 하는지, 아니면 오류를 나타내기 위해 예외가 발생해야 하는지를 나타내는 값을 가져오거나 설정합니다. 기본값은 true입니다. |

### 관련 항목

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
