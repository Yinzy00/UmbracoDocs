---
title: OrderHasOrderNumberSpecification
description: API reference for OrderHasOrderNumberSpecification in Umbraco Commerce
---
## OrderHasOrderNumberSpecification

```csharp
public class OrderHasOrderNumberSpecification : IQuerySpecification<OrderReadOnly>, 
    ISpecification<OrderReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/iqueryspecification-1.md)
* interface [ISpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/ispecification-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Specifications.Order](README.md)

### Constructors

#### OrderHasOrderNumberSpecification

```csharp
public OrderHasOrderNumberSpecification(string orderNumber, StringComparisonType comparisonType)
```


### Properties

#### ComparisonType

```csharp
public StringComparisonType ComparisonType { get; }
```


---

#### OrderNumber

```csharp
public string OrderNumber { get; }
```


### Methods

#### Accept

```csharp
public void Accept(IVisitor visitor)
```


---

#### IsSatisfiedBy

```csharp
public bool IsSatisfiedBy(OrderReadOnly item)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->