---
title: "SetLicense"
second_title: "GroupDocs.Assembly용 .NET API 참조"
description: "컴포넌트에 라이선스를 적용합니다."
type: docs
weight: 30
url: /ko/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

컴포넌트에 라이선스를 적용합니다.

```csharp
public void SetLicense(string licenseName)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseName | String | 전체 파일 이름이든 짧은 파일 이름이든 임베디드 리소스 이름이든 될 수 있습니다. 평가 모드로 전환하려면 빈 문자열을 사용하십시오. |

### 비고

다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 명시적 경로.

2. GroupDocs 구성 요소 어셈블리를 포함하는 폴더.

3. 클라이언트의 호출 어셈블리를 포함하는 폴더.

4. 엔트리(시작) 어셈블리를 포함하는 폴더.

5. 클라이언트의 호출 어셈블리 내에 포함된 리소스.

### 관련 항목

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

컴포넌트에 라이선스를 적용합니다.

```csharp
public void SetLicense(Stream stream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 라이선스를 포함하는 스트림. |

### 비고

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.

### 관련 항목

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Assembly.dll용으로 생성됨 -->
