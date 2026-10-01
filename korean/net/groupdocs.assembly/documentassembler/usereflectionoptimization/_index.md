---
title: "UseReflectionOptimization"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "사용자 정의 형식 멤버를 리플렉션 API를 통해 호출할 때 동적 클래스 생성을 사용하여 최적화할지 여부를 나타내는 값을 가져오거나 설정합니다. 기본값은 true입니다."
type: docs
weight: 60
url: /ko/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

사용자 정의 형식 멤버를 리플렉션 API를 통해 호출할 때 동적 클래스 생성을 사용하여 최적화할지 여부를 나타내는 값을 가져오거나 설정합니다. 기본값은 true입니다.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### 비고

이 최적화를 비활성화하는 것이 바람직한 경우가 있습니다. 예를 들어, 항상 작은 데이터 항목 컬렉션을 다루는 경우 동적 클래스 생성에 따른 오버헤드가 직접 리플렉션 API 호출에 따른 오버헤드보다 더 눈에 띌 수 있습니다.

### 관련 항목

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
