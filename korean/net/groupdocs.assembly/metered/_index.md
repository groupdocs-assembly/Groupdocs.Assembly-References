---
title: "계량식"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "계량 라이선스를 다루는 메서드를 제공합니다."
type: docs
weight: 90
url: /ko/net/groupdocs.assembly/metered/
---
## Metered class

계량 라이선스를 다루는 메서드를 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered)() | 이 클래스의 새 인스턴스를 생성합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | 적절한 공개 및 비공개 계량 키를 지정하여 구성 요소에 대한 계량 라이선스를 활성화합니다. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | 현재 사용된 크레딧 수를 반환합니다. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | 현재 사용된 메가바이트 수를 반환합니다. |

### 예제

이 예제에서는 계량 공개 및 비공개 키를 설정하려는 시도가 이루어집니다:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 관련 항목

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
