---
title: SetLicense
second_title: GroupDocs.Assembly for .NET API 参考
description: 许可组件
type: docs
weight: 30
url: /zh/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

许可组件。

```csharp
public void SetLicense(string licenseName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | String | 可以是完整或短文件名或嵌入资源的名称。 使用空字符串切换到评估模式。 |

### 评论

尝试在以下位置查找许可证：

1.显式路径。

2. 包含 GroupDocs 组件程序集的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入式资源。

### 也可以看看

* class [License](../../license)
* 命名空间 [GroupDocs.Assembly](../../license)
* 部件 [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

许可组件。

```csharp
public void SetLicense(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 包含许可证的流。 |

### 评论

使用此方法从流中加载许可证。

### 也可以看看

* class [License](../../license)
* 命名空间 [GroupDocs.Assembly](../../license)
* 部件 [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
