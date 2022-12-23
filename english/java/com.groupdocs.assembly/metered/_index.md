---
title: Metered
second_title: GroupDocs.Assembly for Java API Reference
description: Provides methods to work with metered licensing.
type: docs
weight: 32
url: /java/com.groupdocs.assembly/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods to work with metered licensing. In this example, an attempt to set metered public and private keys is made:

```

 Metered metered = new Metered();
 metered.setMeteredKey("PublicKey", "PrivateKey");
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Creates a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Enables metered licensing for the component by specifying appropriate public and private metered keys. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Returns the currently consumed number of megabytes. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Returns the currently consumed number of credits. |
### Metered() {#Metered--}
```
public Metered()
```


Creates a new instance of this class.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Enables metered licensing for the component by specifying appropriate public and private metered keys.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | The public metered key. |
| privateKey | java.lang.String | The private metered key. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Returns the currently consumed number of megabytes.

**Returns:**
double - The currently consumed number of megabytes.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Returns the currently consumed number of credits.

**Returns:**
double - The currently consumed number of credits.
