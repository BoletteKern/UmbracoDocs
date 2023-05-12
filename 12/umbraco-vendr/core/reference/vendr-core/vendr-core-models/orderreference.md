---
title: OrderReference
description: API reference for OrderReference in Vendr, the eCommerce solution for Umbraco
---
## OrderReference

```csharp
public class OrderReference : ValueObjectBase
```

**Inheritance**

* class [ValueObjectBase](../../../vendr-common/vendr-common-models/valueobjectbase/)

**Namespace**
* [Vendr.Core.Models](../)

### Constructors

#### OrderReference

```csharp
public OrderReference(Guid orderId, string orderNumber)
```


### Properties

#### OrderId

```csharp
public Guid OrderId { get; }
```


---

#### OrderNumber

```csharp
public string OrderNumber { get; }
```


### Methods

#### Parse

```csharp
public static OrderReference Parse(string input)
```


---

#### DeepClone

```csharp
public override object DeepClone()
```


---

#### ToString

```csharp
public override string ToString()
```


---

#### TryParse

```csharp
public static bool TryParse(string input, out OrderReference orderReference)
```


### Operators

#### OrderReference Implicit

```csharp
public static implicit operator string(OrderReference or)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->