---
title: ValidateOrderLineTaxClassChange
description: API reference for ValidateOrderLineTaxClassChange in Umbraco Commerce
---
## ValidateOrderLineTaxClassChange

```csharp
public class ValidateOrderLineTaxClassChange : ValidationEventBase
```

**Inheritance**

* Class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateOrderLineTaxClassChange

```csharp
public ValidateOrderLineTaxClassChange(OrderReadOnly order, OrderLineReadOnly orderLine, 
    ChangingValue<Guid?> taxClassId)
```


### Properties

#### Order

```csharp
public OrderReadOnly Order { get; }
```


---

#### OrderLine

```csharp
public OrderLineReadOnly OrderLine { get; }
```


---

#### TaxClassId

```csharp
public ChangingValue<Guid?> TaxClassId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->